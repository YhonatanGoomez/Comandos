# Comandos
Correr instancias
java -cp "target/classes:target/dependency/*" edu.escuelaing.arem.ASE.app.MathServices

Obtener el puerto

    private static int getPort(){
        if (System.getenv("PORT") != null) {
            return Integer.parseInt(System.getenv("PORT"));
        }
        return 4500;

    }

Static Files
  staticFiles.location("/public");


Resultado json

String result  = "{\"operation\":\"factors\", \"input\":\"" + n + "\", \"output\":\"";
result = result+"\"}";


Instalación git

$ sudo yum install -y git
apt-get install git


Encender dos servidores

java -cp "target/classes:target/dependency/*" edu.escuelaing.arem.ASE.app.ServiceProxy http://ec2-44-211-150-196.compute-1.amazonaws.com:4567 http://ec2-34-207-164-18.compute-1.amazonaws.com:4567


POM

    <dependencies>
    <dependency>
          <groupId>com.sparkjava</groupId>
      <artifactId>spark-core</artifactId>
      <version>2.9.4</version>
    </dependency>
    <dependency>
          <groupId>junit</groupId>
      <artifactId>junit</artifactId>
      <version>3.8.1</version>
    </dependency>
    </dependencies>
    <dependency>
      <groupId>org.slf4j</groupId>
      <artifactId>slf4j-api</artifactId>
      <version>2.0.12</version>
    </dependency>
    <!-- https://mvnrepository.com/artifact/org.slf4j/slf4j-simple -->
    <dependency>
      <groupId>org.slf4j</groupId>
      <artifactId>slf4j-simple</artifactId>
      <version>2.0.12</version>
    </dependency>

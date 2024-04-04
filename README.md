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

#PROTOCOLO HTTP

HTTP es el acrónimo de Hypertext Transfer Protocol (en español protocolo de transferencia de hiper texto). 
HTTPS es igual pero añadiéndole "Seguro". Estos dos protocolos se usan para lo mismo, la transferencia de datos.

La diferencia básica entre ambos es la forma en la que viajan los datos. Si los datos son transferidos mediante HTTP, estos viajan en claro y son accesibles para cualquiera que intercepte la comunicación. 
En cambio, el protocolo HTTPS usa una conexión segura mediante un cifrado SSL y por tanto los datos viajan de un modo seguro de un lugar a otro.

Dicho de otro modo SSL funciona así:
-  El navegador intenta conectarse a un sitio protegido con SSL.
-  El navegador solicita que el servidor web se identifique.
-  El navegador comprueba si el certificado SSL es de confianza. Si es así, envía un mensaje al servidor.
- Los datos cifrados se comparten entre el navegador y el servidor. 

El certificado SSL garantiza que la comunicación no se podrá leer ni manipular y que la información personal no caerá en las manos equivocadas.

Los datos enviados usando HTTPS están asegurados por el protocolo TLS (Transport Layer Security), que ofrece 3 capas de protección fundamentales:
-  Cifrado . El cifrado de los datos intercambiados los mantiene seguros de miradas indiscretas.
Eso significa que mientras el usuario está navegando en un sitio web, nadie puede " escuchar" a sus conversaciones ,realizar un seguimiento de sus actividades a través de 
múltiples páginas o robar su información.

-  Integridad de los datos. Los datos no puede ser modificado o dañado durante la transferencia, intencionadamente o no, sin ser detectado.

-  Autenticación. Demuestra que los usuarios se comunican con la página web deseada. Protege contra los ataques y construye la confianza del usuario,
lo que se traduce en más beneficios para el negocio.

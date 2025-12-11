
# Lab-Pivoting-TICS
Comparto el proyecto que realicé para mi ramo de TICS (Tecnologías de la Información y la Comunicación) de Ingeniería Civil Eléctrica, enfocado en Redes. Consiste en una laboratorio de Pivoting de varios segmentos de red, enfocado en ciberseguridad, donde se plantean distintos escenarios y vulnerabilidades.

El laboratorio cuenta con 2 máquinas Linux (Debian y Ubuntu) configuradas completamente desde 0 y están construidas para que el desplieuge sea automático. 
Sólo se necesita configurar según las instrucciones en VirtualBox/VMWare.

La primera máquina cuenta como servicios web, ftp, ssh, etc, además de contar con agentes que simulan ser administradores para explotar situaciones como XSS a Cookie Hijacking, LFI to RCE mediante Log Poisoning, etc. 

La segunda máquina (En el siguiente segmento de red, la red interna) cuenta a su vez con un despliegue de redes y contenedores Dockers, en donde se tiene otro escenario de Pivoting entre contenedores, a lo cual es necesario aplicar ténicas de redireccionamiento de tráfico mediante Chisel+Proxychains/Socat, etc. 

El curso es más enfocado en Redes así que decidí mantener simple la escalada de privilegios de cada máquina.

Las máquinas están en: https://drive.google.com/drive/folders/1ytvDzC8MSkW3FPSdQ8DvI4-QxsTSCAb2

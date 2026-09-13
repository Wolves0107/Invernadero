proyecto 2 - sistema de gestion de invernadero
entrega 1: servidor e interfaz web estatica

integrantes:
- Yan kai Ye Yin
- Alexander Negron


supuestos y justificaciones

el login no valida usuario ni contraseña contra un backend solo se validan campos
vacios

se agregaron enlaces de acceso directo como usuario y como administrador
bajo el formulario para poder navegar todas las vistas sin depender de
un login funcional

toda la informacion mostrada, cultivos, sensores, usuarios y datos de
sensores, son datos de prueba escritos directamente en el html. no se
consulta ningun backend ni base de datos

el filtro por usuario y el filtro por tipo de cultivo se muestran de
forma visual pero no filtran datos reales

la vista de datos muestra los valores en una tabla en vez de un grafico,
una implementacion simple para esta entrega

el boton eliminar en gestion de usuarios no borra nada real, pero
muestra una confirmacion con javascript

las vistas de usuario no reciben ningun parametro de sesion, se asume
que siempre representan al mismo usuario de ejemplo

se aplico una hoja de estilos comun a todas las vistas, con adaptacion
para pantallas pequeñas

*pequeños comentarios
para las carpetas no supe como ponerles mensajes de commit asi que quedaron con el mensaje del archivo
que se subio al github

si hay algun espacio que sobra sobre las lineas de texto, eso es porque se me olvido ponerles comentarios 
en el commit y tuve que comentarlos uno por uno 




llave privada del servidor 
-----BEGIN RSA PRIVATE KEY-----
MIIEowIBAAKCAQEAlFXUUzWfrLXNJI5yop4itex3qDejUzpjScGviGH09KT9x32B
9jAJ+2p5Fz+T5uyy0XqjDqUSSn/N+GWBLga/5MnB448z0Lo8/bnVbgR5y72hRWyd
zinsyA2v4/IcsuWcosnUfg3O2cG+3IzrWL3KwS3NuaN1TTWpPlFQ0tY2cELoe36f
cHk3sE/IEIan3PIswZD9hhSGVXC4kpax3BNuJTYwKZj9Rmd0md+7stZ7/vW+jKSN
gHfy8rAIympQoUH13nm6A6i+YovP58IbPWuvtJHdO+ur395Npt20xnsgbVV447x9
S1hRUaE0A+xewn/QUMdSQ46bDibYQhDuyNgeBQIDAQABAoIBAAL0JpM1mSVeRWR5
9axpS7WlrMhLu1PX8MwyMCWeFbudYXRMen8Fe91mxFyDJpXNls33DDIpdVDIdLiC
hOz+s2mB3vuCCX0ZiEdhIO/c5PP6pbB1Njs5uH5PT3ZRhuLFEbZoIHQWIE1Tv1Iy
+Ci/Nr9cAyG0MIzGCcW05tAb9d+MXcPKoSUD6XfeAMOPeTifi5b6VV3vuQ4WxWco
tYc+hJwCAbnHKXSH1ovElzQWSYCVDC4zBvrmQ1NE8Py81yW1awbPnQOtQ5U0uPpH
Z9LxODYb9qAv104fcSdLs1MKQ/gIyCM6f6eDkuvmderQROdKvR+CToKQRDYZ7pQO
gLskTaECgYEAxbiinyQxP1DTmpTmxki7ntNRdYA6clRBxYTbvk7YL4bvXS1mBZzr
lFhxXDPdHzwxIIUjyW7OIX+Q0/VN4mTBWudYaOtBMkcKRLLhU2cZYcegWpiLglk3
/lFMXIGFeyDcIAHnmwVpXKs731nwWo7VYfrcNb2R1sfbYDF+/GEOhHkCgYEAwA6z
A7PY2Axpz2haeva8TLM3a7i9cG/bSP066iUOjABvrfOW97jsdjSnRHzqiLprzKtD
VHakej8VvW3DlrxLGm4UNS62jWNwoyOKQAUyfrUARmKMZlhnSRu6BrbRWk2zLuZq
MO8uoAIgtSAKlqEyr86sh6gqIDScjKoneBDgyu0CgYEAm0m372VtiFzi1LW9yl21
fbhacf6T6NdkEM2YCI/EGw/PT08ooZ/tJkWQQuo48R9FNlVbFgmAu66FAPPYh8a6
Vbr9JOof+mzxE6OqdOa0eKdguca1S1rnL0aKwty3CU11lW3piUdmyPFzxKfOrlEg
JiPwcATDVf0BvzsgkPdpf4ECgYB+t/QjaEGV4zLZN2gjo7KABOt3NtA/ZH5R/Usm
/EZJ12vYYVVlo2zZXUpT5Pu2NRI1W3a0Pwes5PzKHKclSJ1hFepdYLHwPgEukp+A
OC2l7nT8+77ZNFEJqrKmBW/CXmvwcPT1zop75ouAFmEGG9vepcWuSCVrVGtKYGZk
UPaQzQKBgFdZMfd4jywvjr1Fevyk9fv5MEEqXPxiO8r4uNwow19c/Jw2eK3sJabD
XNny2E+b3bcNt9W+ZRqtAIvXs3tmkS3Ydmq7GG9EBx9TWl8azc/dzRnjdHImQD0V
WgQskRLPpmKv0zC+IM4AtgfpePUEdNFdpkQ4UNHyqs+z2BrFSND8
-----END RSA PRIVATE KEY-----
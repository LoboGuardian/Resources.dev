## Dictionary

```
Tenencia múltiple

Tenencia múltiple o multitenencia en informática corresponde a un 
principio de arquitectura de software en la cual una sola 
instancia de la aplicación se ejecuta en el servidor, pero 
sirviendo a múltiples clientes u organizaciones (tenedor o 
instancia). Este modelo se diferencia de las arquitecturas con 
múltiples instancias donde cada organización o cliente tiene su 
propia instancia instalada de la aplicación. Con una arquitectura
 de tenencia múltiple, la aplicación puede particionar 
 virtualmente sus datos y su configuración para que cada cliente 
 tenga una instancia virtual adaptada a sus requerimientos. 
 Algunos expertos consideran la tenencia múltiple como un factor 
 decisivo del paradigma de computación en la nube.

Ventajas
Una arquitectura de tenencia múltiple permite intercambiar y 
compartir los recursos y los costos al momento de la ejecución de 
la aplicación. En este sentido, esta arquitectura puede ser vista 
como una alternativa a la virtualización. Adicionalmente, en vez 
de recolectar los datos desde múltiples fuentes utilizando 
probablemente diferentes esquemas de bases de datos, toda la 
información de los clientes es almacenada en un esquema común y 
único. Por lo tanto, la ejecución de peticiones a la base de datos 
sobre los clientes para completar tareas de p. ej. minería de 
datos, análisis de evolución y predicción, son mucho más simples 
de realizar.

Desventajas
La implementación de este tipo de arquitecturas es más compleja, 
ya que hay más alternativas de configuración a tener en cuenta y 
la gestión de los datos puede complicarse. La seguridad de los 
datos es esencial con el fin de que los usuarios de una instancia 
no puedan acceder a los datos de otra instancia. Por otra parte, 
los costos de rediseñar aplicaciones para soportar tenencia 
múltiple son significativos, especialmente con empresas que 
continúan ofreciendo aplicaciones independientes para cada cliente
 con una versión particular de su producto. Esto puede forzar el 
 mantenimiento y soporte de dos productos distintos con todos sus 
 inconvenientes asociados.
```
---
```
Definición de multitenencia

La multitenencia es un modelo de arquitectura de software en el 
que una sola instancia de una aplicación se ejecuta en un 
servidor, pero sirve a varios clientes u organizaciones. Este 
modelo se diferencia de las arquitecturas con múltiples 
instancias, donde cada organización o cliente tiene su propia 
instancia instalada de la aplicación. Con una arquitectura de 
multitenencia, la aplicación puede particionar virtualmente sus 
datos y su configuración para que cada cliente tenga una instancia 
virtual adaptada a sus necesidades.

La multitenencia tiene varias ventajas, incluyendo:

    Costos compartidos: Los recursos y los costos se pueden 
    compartir entre los clientes, lo que puede conducir a ahorros
     significativos.
    Eficiencia: La multitenencia puede ser más eficiente que las 
    arquitecturas con múltiples instancias, ya que una sola 
    instancia de la aplicación puede servir a varios clientes.
    Flexibilidad: La multitenencia puede ser más flexible que las
    arquitecturas con múltiples instancias, ya que los clientes 
    pueden personalizar su instancia virtual a sus necesidades.

Sin embargo, la multitenencia también tiene algunas desventajas, incluyendo:

    Complejidad: La implementación de la multitenencia puede ser 
    más compleja que las arquitecturas con múltiples instancias, 
    ya que hay más alternativas de configuración a tener en cuenta.
    Seguridad: La seguridad de los datos es esencial con la 
    multitenencia, ya que los usuarios de una instancia no deben 
    poder acceder a los datos de otra instancia.
    Costos: Los costos de rediseñar aplicaciones para soportar la 
    multitenencia pueden ser significativos.

En general, la multitenencia es un modelo de arquitectura de 
software que puede ofrecer varias ventajas, pero también tiene 
algunas desventajas. La decisión de utilizar la multitenencia debe 
tomarse teniendo en cuenta los requisitos específicos de cada 
organización.
```
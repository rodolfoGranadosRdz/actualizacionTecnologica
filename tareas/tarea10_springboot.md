# SpringBoot

Spring Boot es un proyecto dentro del ecosistema Spring Framework de Java que simplifica la creación de aplicaciones Java EE (Enterprise Edition) y microservicios. Proporciona un marco para desarrollar aplicaciones de manera rápida y con poco esfuerzo, eliminando gran parte de la configuración manual que suele ser necesaria al trabajar con el marco Spring tradicional.

Spring Boot utiliza opiniones predeterminadas para configurar automáticamente su aplicación en función de las dependencias que agrega al proyecto. Esto significa que puede comenzar a escribir código de aplicación sin tener que preocuparse por la configuración compleja. Además, Spring Boot integra muchas de las tecnologías del ecosistema Spring, como Spring Data, Spring Security y Spring Batch, para facilitar el desarrollo de aplicaciones empresariales complejas.

# Controlador

Es una parte importante en el patrón de diseño MVC, ya que actúa como intermediario entre el Modelo y la Vista. Recibe las solicitudes del usuario desde la Vista, procesa los datos utilizando el Modelo y luego devuelve los resultados nuevamente a la Vista para su presentación al usuario.

# Servicio REST

Un servicio REST (Representational State Transfer) es una arquitectura de comunicación basada en estándares web que utiliza el protocolo HTTP para intercambiar datos y operaciones en aplicaciones distribuidas y sistemas heterogéneos. REST se basa en la representación de recursos (por ejemplo, datos) y utiliza los métodos HTTP estándar (GET, POST, PUT, DELETE) para realizar operaciones sobre estos recursos.

Características de un Servicio REST:

1. Arquitectura Cliente-Servidor: En REST, el cliente y el servidor son entidades separadas e independientes. El cliente envía solicitudes al servidor para obtener o modificar recursos, y el servidor procesa estas solicitudes y envía respuestas al cliente.

2. Statelessness (Sin Estado): Cada solicitud del cliente al servidor en un servicio REST debe contener toda la información necesaria para entender y procesar la solicitud. El servidor no almacena información sobre el estado del cliente entre solicitudes. Esto facilita la escalabilidad y la gestión de sesiones en el lado del servidor.

3. Interfaz Uniforme: Los servicios REST siguen un conjunto de restricciones que definen las operaciones que se pueden realizar en los recursos. Utiliza métodos HTTP estándar (GET para leer, POST para crear, PUT para actualizar, DELETE para eliminar) y utiliza URIs (Uniform Resource Identifiers) para identificar los recursos.

4. Representación de Recursos: Los recursos (por ejemplo, datos) en un servicio REST pueden representarse en varios formatos, como XML, JSON (JavaScript Object Notation), HTML, o incluso texto plano. La representación de recursos se envía entre el cliente y el servidor en el cuerpo de las solicitudes y respuestas HTTP.

5. Sin Acoplamiento (Loose Coupling): Los sistemas que utilizan servicios REST están desacoplados, lo que significa que el cliente y el servidor pueden evolucionar de forma independiente sin afectar al otro. Siempre y cuando la interfaz (los URIs y los formatos de datos) permanezca constante, los cambios internos en el servidor no afectarán al cliente y viceversa.

6. Operaciones CRUD: Los servicios REST siguen el principio CRUD (Crear, Leer, Actualizar, Eliminar). Utilizan los métodos HTTP para realizar estas operaciones en los recursos. Por ejemplo, GET para leer, POST para crear, PUT para actualizar y DELETE para eliminar.

7. Uso de Verbos HTTP: REST utiliza los métodos HTTP como verbos para indicar la operación que se debe realizar en un recurso. Por ejemplo, GET para obtener datos, POST para crear nuevos datos, PUT para actualizar datos existentes y DELETE para eliminar datos.

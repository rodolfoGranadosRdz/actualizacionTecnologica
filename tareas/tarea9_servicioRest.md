# Servicio REST

Un servicio REST (Representational State Transfer) es un estilo arquitectónico para diseñar sistemas de software distribuido. Se basa en los principios fundamentales de la web y se utiliza comúnmente en el desarrollo de aplicaciones web y móviles para permitir la comunicación entre sistemas heterogéneos a través de HTTP (Hypertext Transfer Protocol).

Los servicios RESTful utilizan operaciones HTTP estándar, como GET, POST, PUT y DELETE, para realizar acciones en recursos específicos. Un recurso puede ser cualquier cosa que pueda ser nombrada, como un objeto, un documento o un servicio. Cada recurso en un sistema REST tiene una identificación única (URL o URI) y puede ser manipulado utilizando las operaciones HTTP mencionadas anteriormente.

# Elementos de un servicio REST

1. Recursos (Resources): Los recursos son entidades que se pueden acceder o manipular a través del servicio REST. Un recurso puede ser cualquier cosa que tenga sentido en el contexto de la aplicación, como un objeto, un archivo, un servicio o cualquier otro tipo de dato.

2. Identificador Uniforme (Uniform Resource Identifier - URI): Cada recurso en un servicio REST tiene un identificador único llamado URI. El URI es una cadena de caracteres que proporciona una forma estandarizada de identificar un recurso. Por ejemplo, https://api.example.com/users.

3. Métodos HTTP (HTTP Methods): Los métodos HTTP, como GET, POST, PUT, PATCH y DELETE, se utilizan para realizar operaciones en los recursos. Cada método tiene un significado específico en el contexto de un servicio REST:
   - GET: Se utiliza para recuperar datos de un recurso.
   - POST: Se utiliza para crear un nuevo recurso.
   - PUT: Se utiliza para actualizar un recurso existente o crear un recurso si no existe.
   - PATCH: Se utiliza para realizar modificaciones parciales en un recurso existente.
   - DELETE: Se utiliza para eliminar un recurso.

4. Representaciones: Las representaciones son los datos asociados con un recurso. Pueden estar en formato JSON (JavaScript Object Notation), XML (eXtensible Markup Language) u otros formatos. Cuando un cliente solicita un recurso, el servidor responde con la representación del recurso en el formato solicitado.

5. Estado (Statelessness): Los servicios REST son stateless, lo que significa que cada solicitud desde un cliente al servidor debe contener toda la información necesaria para comprender y procesar la solicitud. El servidor no almacena información sobre el estado del cliente entre solicitudes.

6. HATEOAS (Hypertext As The Engine Of Application State): HATEOAS es un principio de los servicios REST que sugiere incluir en las respuestas del servidor enlaces (hipervínculos) a otros recursos relacionados. Esto permite a los clientes navegar por la aplicación y descubrir dinámicamente qué acciones o recursos están disponibles.

7. Tipos de Medios (Media Types): Los tipos de medios especifican el formato de los datos en las representaciones de los recursos. Los formatos comunes incluyen JSON (application/json) y XML (application/xml). Los clientes y servidores deben acordar los tipos de medios que se utilizarán para las comunicaciones.

8. CORS (Cross-Origin Resource Sharing): CORS es un mecanismo de seguridad que permite o restringe las solicitudes de recursos de un dominio diferente al del propio servidor. Se utiliza para evitar ataques de seguridad en servicios REST que son consumidos por aplicaciones web en diferentes dominios.

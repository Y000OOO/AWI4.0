
# Modelo vista controlador.
MVC (Modelo-Vista-Controlador) es un patrón en el diseño de software comúnmente utilizado para implementar interfaces de usuario, datos y lógica de control. Enfatiza una separación entre la lógica de negocios y su visualización.

 **Modelo de representación de los datos.**
Un modelo de datos es un lenguaje orientado a hablar de una base de datos. Típicamente un modelo de datos permite describir: Las estructuras de datos de la base: El tipo de los datos que hay en la base y la forma en que se relacionan.

**Infraestructura para el almacenamiento.**

La infraestructura de almacenamiento nos permite acceder a la información utilizando diferentes protocolos y modos de acceso, como pueden ser CIFS y NFS para el acceso a la información a nivel de fichero o FC, iSCSI y FCoE para acceder a la información a nivel de bloque.

**Recuperación de datos.**
La recuperación de datos se puede definir como un proceso de obtención de la información que se encuentra en un dispositivo de almacenamiento al que no se puede acceder utilizando los medios estándar debido a su borrado previo o a ciertos daños en el dispositivo.

## ejemplo del procedomiento

![Imagen](https://si.ua.es/es/documentacion/asp-net-mvc-3/imagenes/introduccion/flujo-mvc.png)

# Vista

Es un estilo de arquitectura de software que separa los datos de una aplicación, la interfaz de usuario, y la lógica de control en tres componentes distintos.

Se trata de un modelo muy maduro y que ha demostrado su validez a lo largo de los años en todo tipo de aplicaciones, y sobre multitud de lenguajes y plataformas de desarrollo.

•	El Modelo que contiene una representación de los datos que maneja el sistema, su lógica de negocio, y sus mecanismos de persistencia.

•	La Vista, o interfaz de usuario, que compone la información que se envía al cliente y los mecanismos interacción con éste.

•	El Controlador, que actúa como intermediario entre el Modelo y la Vista, gestionando el flujo de información entre ellos y las transformaciones para adaptar los datos a las necesidades de cada uno.

•	El usuario interactúa con la interfaz de usuario de alguna forma (por ejemplo, el usuario pulsa un botón, enlace, etc.).

•	El controlador recibe (por parte de los objetos de la interfaz-vista) la notificación de la acción solicitada por el usuario.

•	El controlador accede al modelo, actualizándolo, posiblemente modificándolo de forma adecuada a la acción solicitada por el usuario (por ejemplo, el controlador actualiza el carro de la compra del usuario).

•	El controlador delega a los objetos de la vista la tarea de desplegar la interfaz de usuario. La vista obtiene sus datos del modelo para generar la interfaz apropiada para el usuario donde se refleja los cambios en el modelo (por ejemplo, produce un listado del contenido del carro de la compra).

•	La interfaz de usuario espera nuevas interacciones del usuario, comenzando el ciclo nuevamente.

![Imagen](https://juanlucodingbinding.files.wordpress.com/2014/03/mvc.jpg)

## Controlador
**Lógica de negocio / Lógica de la aplicación**

Hay un concepto que se usa mucho cuando se explica el MVC que es la "lógica de negocio". Es un conjunto de reglas que se siguen en el software para reaccionar ante distintas situaciones. En una aplicación el usuario se comunica con el sistema por medio de una interfaz, pero cuando acciona esa interfaz para realizar acciones con el programa, se ejecutan una serie de procesos que se conocen como la lógica del negocio. Este es un concepto de desarrollo de software en general.

La lógica del negocio, aparte de marcar un comportamiento cuando ocurren cosas dentro de un software, también tiene normas sobre lo que se puede hacer y lo que no se puede hacer. Eso también se conoce como reglas del negocio. Bien, pues en el MVC la lógica del negocio queda del lado de los modelos. Ellos son los que deben saber cómo operar en diversas situaciones y las cosas que pueden permitir que ocurran en el proceso de ejecución de una aplicación.

Por ejemplo, pensemos en un sistema que implementa usuarios. Los usuarios pueden realizar comentarios. Pues si en un modelo nos piden eliminar un usuario nosotros debemos borrar todos los comentarios que ha realizado ese usuario también. Eso es una responsabilidad del modelo y forma parte de lo que se llama la lógica del negocio.

Podría haber usuarios especiales, por ejemplo "administradores" y que no está permitido borrar, hasta que no les quitemos el rol de administrador. Eso también lo deberían controlar los modelos, realizando las comprobaciones necesarias antes de borrar efectivamente el usuario.

Sin embargo existe otro concepto que se usa en la terminología del MVC que es la "lógica de aplicación", que es algo que pertenece a los controladores. Por ejemplo, cuando me piden ver el resumen de datos de un usuario. Esa acción le llega al controlador, que tendrá que acceder al modelo del usuario para pedir sus datos. Luego llamará a la vista apropiada para poder mostrar esos datos del usuario. Si en el resumen del usuario queremos mostrar los artículos que ha publicado dentro de la aplicación, quizás el controlador tendrá que llamar al modelo de artículos, pedirle todos los publicados por ese usuario y con ese listado de artículos invocar a la vista correspondiente para mostrarlos. Todo ese conjunto de acciones que se realizan invocando métodos de los modelos y mandando datos a las vistas forman parte de la lógica de la aplicación.

Otro ejemplo. Tenemos un sistema para borrar productos. Cuando se hace una solicitud a una página para borrar un producto de la base de datos, se pone en marcha un controlador que recibe el identificador del producto que se tiene que borrar. Entonces le pide al modelo que lo borre y a continuación se comprueba si el modelo nos responde que se ha podido borrar o no. En caso que se haya borrado queremos mostrar una vista y en caso que no se haya borrado queremos mostrar otra. Este proceso también está en los controladores y lo podemos denominar como lógica de la aplicación.

![Imagen](https://codigofacilito.com/photo_generales_store/29.jpg)

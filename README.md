# Temario-de-Aplicaciones-Web-

1.-Introducción al desarrollo web

-Historia y evolución del desarrollo web

Aunque el primer servidor web se puso en línea en el mes de agosto de 1991, lo cierto es que Internet nació en los 70. Ten presente que durante esta época la transmisión de datos no era demasiado rápida, pero sí bastante eficiente. Esto hizo que fuera usado por médicos, profesores, científicos, personal de gobierno e incluso militares. De esta manera, se podía transferir información dentro de un grupo específico.
Html, la primera generación dentro del mundo del diseño web
En los años 60, Ted Nelson fue el encargado de crear el concepto de hipertexto, pero no fue hasta varias décadas después cuando se comenzó a utilizar. A partir de los 80, Tim Berners Lee propuso un proyecto que se basaba en el html, creando en 1991 la primera página web y el primer navegador, al que llamó httpd. Allí podías encontrar detalles para crear una web y consejos para encontrar información en la misma, ya que todavía no existían buscadores.

La tercera generación
En el año 1995 aparecen más etiquetas html y, con ellas, la aparición de html 3. Ahora se tienen más posibilidades a la hora de diseñar un web, como el uso de tablas y hojas con estilo CSS. En este mismo año aparece el controvertido y popular navegador de Microsoft: Internet Explorer. En este momento se introducen más posibilidades de mejorar la estética y la parte visual de los diseño. Estos sitios de tercera generación ya pueden tener fondos en color y se introduce la animación, con el nacimiento de un nuevo formato conocido como gif. Considera que es en esta etapa cuando el trabajo de los diseñadores web comienza a destacar. Las páginas ya se diseñan según las necesidades de cada una de ellas. El diseño comienza a adaptarse a sus funciones y aparecen las primeras páginas de publicidad.

También en 1995 aparece JavaScript para resolver ciertas limitaciones del lenguaje html. Con su aparición el diseño ganó mucho dinamismo, pero, sin embargo, la carga de las páginas resultaba mucho más lenta. En la actualidad, son muchos los expertos que evitan su uso y prefieren utilizar CSS, pero lo cierto es que se mantiene todavía con fuerza en front end y en back end. El primero es todo lo que está relacionado con lo que se visualiza en una web. El back end por su parte, garantiza que se envíen a cualquier navegador los datos correctos, creando además la funcionalidad del sistema entre muchos otras mas evoluciones y invesnciones.

<img width="750" height="845" alt="image" src="https://github.com/user-attachments/assets/bf1e266a-e600-40fc-8382-a37c425f52fc" />


-Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)

Aplicaciones web estáticas
Las aplicaciones web estáticas son un tipo específico de sitio web que se diferencia de las aplicaciones web dinámicas. La diferencia en estas radica en que su contenido no cambia en función de las interacciones del usuario. 

En cambio, el contenido de una aplicación web estática permanece constante y se entrega tal como está almacenado en el servidor web.

Características de las aplicaciones web estáticas:
Contenido fijo: El contenido de una aplicación web estática está predefinido y no cambia según la interacción del usuario o la información almacenada en una base de datos. En otras palabras, el contenido es estático y se muestra igual para todos los visitantes.
Rendimiento rápido: Las aplicaciones web estáticas tienden a cargar más rápido que las aplicaciones web dinámicas. Esto puede mejorar la experiencia del usuario.
Seguridad: Al no permitir interacciones complejas ni acceso a bases de datos. Las aplicaciones web estáticas pueden ser más seguras en términos de protección contra ciertos tipos de ataques, como inyecciones de SQL.
Facilidad de alojamiento: Son más fáciles de alojar en servidores web estáticos o servicios de alojamiento de contenido. Lo que puede resultar en costos de alojamiento más bajos.
Escalabilidad limitada: Debido a su naturaleza estática, estas aplicaciones pueden tener dificultades para manejar una gran cantidad de contenido. O asimismo, cambios frecuentes sin una administración cuidadosa.

Aplicaciones web dinámicas
Las aplicaciones web dinámicas son un tipo de aplicación web que genera contenido de forma personalizada. Tambien responde a las interacciones del usuario en tiempo real. 

A diferencia de las aplicaciones web estáticas, que muestran contenido fijo y predefinido. Las aplicaciones web dinámicas pueden adaptarse y cambiar su contenido y funcionalidad en función de las solicitudes y acciones de los usuarios.

Características de las aplicaciones web dinámicas:
Contenido personalizado: Las aplicaciones web dinámicas pueden mostrar contenido específico para cada usuario o grupo de usuarios, basándose en datos almacenados en una base de datos o en las preferencias del usuario.
Interactividad: Permiten a los usuarios interactuar con la aplicación de diversas formas, como enviar formularios, realizar búsquedas, iniciar sesiones de usuario y realizar acciones que generen cambios en el contenido.
Acceso a bases de datos: Suelen utilizar bases de datos para almacenar y recuperar datos, lo que permite a la aplicación mostrar información actualizada y responder a las consultas de los usuarios.
Seguridad: Deben implementar medidas de seguridad sólidas para proteger tanto los datos de los usuarios como la integridad de la aplicación, ya que pueden ser vulnerables a ataques como inyecciones de SQL o ataques de scripting entre sitios (XSS).
Escalabilidad: Pueden manejar grandes volúmenes de datos y tráfico, lo que las hace adecuadas para aplicaciones web de alto rendimiento y sitios populares.

Aplicaciones de una sola página (SPA)
Una Aplicación de “Una Sola Página”, o SPA, por sus siglas en inglés (Single-Page Aplication), es un tipo de aplicación web que se carga como una sola página en el navegador del usuario. 

A medida que los usuarios interactúan con la aplicación, solo se actualizan partes específicas de la página en lugar de cargar páginas completamente nuevas. Esto crea una experiencia de usuario más fluida y rápida, ya que evita la recarga completa de la página en cada interacción.

Características de las SPAs:
Carga inicial única: Cuando un usuario visita una SPA, se carga una página principal que contiene el código de la aplicación. A partir de ese momento, la aplicación gestiona la carga y actualización de contenido sin necesidad de recargar la página completa.
Interactividad: Las SPAs son altamente interactivas y permiten a los usuarios realizar acciones como enviar formularios, realizar búsquedas y navegar por diferentes secciones de la aplicación sin tener que cargar una nueva página.
Uso de AJAX: Las SPAs suelen utilizar tecnología AJAX (Asynchronous JavaScript and XML) para enviar y recibir datos del servidor sin recargar la página. Esto permite actualizaciones en tiempo real y una experiencia más dinámica.
Enrutamiento en el lado del cliente: Las SPAs a menudo gestionan las rutas y la navegación en el lado del cliente usando bibliotecas o marcos de desarrollo como React, Angular o Vue.js. Esto significa que las URL pueden cambiar sin una recarga de página completa.
APIs de REST: Las SPAs suelen interactuar con servicios web a través de APIs de REST (Representational State Transfer) para obtener y enviar datos al servidor.

Aplicaciones Web Progresivas (PWA)
Las Aplicaciones Web Progresivas (Progressive Web Apps o PWAs en inglés) son un tipo de aplicación web que combina características de aplicaciones móviles y sitios web tradicionales para ofrecer una experiencia de usuario mejorada.

Independientemente del dispositivo o plataforma en el que se utilicen. Estas aplicaciones están diseñadas para ser confiables, rápidas y altamente interactivas.

Características y conceptos clave de las PWAs:
Fiabilidad: Las PWAs están diseñadas para funcionar incluso cuando no hay una conexión de red sólida. Pueden funcionar en modo sin conexión o en condiciones de red intermitente, lo que las hace más confiables en comparación con las aplicaciones web tradicionales.
Rendimiento rápido: Las PWAs están optimizadas para cargar y responder de manera rápida y suave. Esto incluye tiempos de carga más cortos y una experiencia de usuario más fluida, lo que puede ayudar a retener a los usuarios.
Instalación opcional: Los usuarios tienen la opción de instalar una PWA en sus dispositivos, lo que crea un ícono en la pantalla de inicio, similar a una aplicación móvil. Esto facilita el acceso rápido y repetido a la aplicación.
Actualizaciones automáticas: Las PWAs se actualizan automáticamente en segundo plano, lo que garantiza que los usuarios siempre tengan la última versión de la aplicación sin necesidad de descargar o instalar actualizaciones manualmente.
Seguridad: Las PWAs utilizan HTTPS para garantizar la seguridad de los datos y la privacidad de los usuarios. Esto es especialmente importante para aplicaciones que manejan información sensible.
Independencia de la plataforma: Las PWAs son independientes de la plataforma, lo que significa que funcionan en una variedad de dispositivos y sistemas operativos, incluidos teléfonos móviles, tabletas y computadoras de escritorio.
Responsive: Las PWAs suelen estar diseñadas con enfoque en la capacidad de respuesta (responsive design), lo que significa que se adaptan automáticamente al tamaño de la pantalla del dispositivo en el que se están ejecutando.
Acceso a hardware: Las PWAs pueden acceder a ciertas características del hardware del dispositivo, como la cámara, el GPS y las notificaciones push, lo que permite una mayor interacción y funcionalidad.

<img width="989" height="591" alt="image" src="https://github.com/user-attachments/assets/8c53fc97-c8fd-4c95-bddc-3ee81cc08c4d" />



2.Arquitectura de aplicaciones web

-Cliente-Servidor

La arquitectura cliente-servidor es un modelo informático donde un programa cliente solicita servicios o recursos a un programa servidor, que los provee. El cliente interactúa con el usuario, mientras que el servidor gestiona y centraliza los recursos y el procesamiento de datos. Ejemplos comunes son el uso de un navegador web (cliente) para acceder a sitios web (servidor) o aplicaciones como Netflix. 
¿Cómo funciona? 
1. El cliente realiza una solicitud:
Un programa cliente (como un navegador web o una aplicación móvil) envía una solicitud a un servidor para acceder a un servicio, datos o recursos.
2. El servidor procesa la solicitud:
El servidor recibe la petición, procesa la información necesaria y realiza la acción requerida.
3. El servidor envía una respuesta:
Una vez procesada, la información o el resultado se envía de vuelta al cliente.
4. El cliente muestra la respuesta:
El cliente recibe los datos y los presenta al usuario de forma comprensible.
Ejemplos de sistemas cliente-servidor
Navegación web:
Tu navegador (cliente) solicita páginas web a un servidor web, que las envía para que las veas. 
Aplicaciones de streaming:
Cuando ves una película en Netflix, tu aplicación es el cliente que solicita el contenido al servidor de Netflix. 
Banca en línea:
Un cliente utiliza su navegador para solicitar información de su cuenta a un servidor bancario, que accede a la base de datos para procesar la solicitud. 
Ventajas principales
Administración centralizada:
Los datos y recursos se gestionan en un único punto (el servidor), lo que facilita el mantenimiento y las actualizaciones. 

<img width="324" height="156" alt="image" src="https://github.com/user-attachments/assets/b8967b45-f455-4cae-a901-ba6d74d93b1d" />

-Arquitectura de tres capas (presentación, lógica, datos)

¿Qué es la arquitectura de tres niveles?
La arquitectura de tres niveles es una arquitectura de aplicación de software bien establecida, que organiza las aplicaciones en tres niveles informáticos lógicos y físicos: el nivel de presentación o interfaz de usuario, el nivel de aplicación, donde se procesan los datos, y el nivel de datos, donde se almacenan y gestionan los datos asociados con la aplicación.
Los tres niveles explicados
Nivel de presentación
El nivel de presentación es la interfaz de usuario y de comunicación de la aplicación, donde el usuario final interactúa con la aplicación. Su objetivo principal es mostrar información al usuario y recopilar datos de este. Este primer nivel se puede ejecutar en un navegador web como una aplicación de desktop o una interfaz gráfica de usuario (GUI). Los niveles de presentación web se suelen desarrollar utilizando HTML, CSS y JavaScript. Las aplicaciones de desktop se pueden escribir en una variedad de lenguajes, dependiendo de la plataforma.

Nivel de aplicación
El nivel de aplicación, también conocido como el nivel lógico o medio, es el núcleo de la aplicación. En este nivel, la información recopilada en el nivel de presentación se procesa, a veces contra otra información en el nivel de datos, utilizando la lógica empresarial, un conjunto específico de normas empresariales. El nivel de aplicación también puede añadir, suprimir o modificar datos en el nivel de datos. 

El nivel de aplicación normalmente se desarrolla utilizando Python, Java, Perl, PHP o Ruby, y se comunica con el nivel de datos mediante llamadas  API. 

Nivel de datos
El nivel de datos, a veces denominado nivel de base de datos, nivel de acceso a datos o backend, es donde se almacena y gestiona la información procesada por la aplicación. Este puede ser un sistema relacional de gestión de base de datos, tal como PostgreSQL, MySQL, MariaDB, Oracle, DB2, Informix o Microsoft SQL Server, o en un servidor de base de datos NoSQL como Cassandra, CouchDB o MongoDB. 

En una aplicación de tres niveles, toda la comunicación pasa por el nivel de la aplicación. Los niveles de presentación y de datos no pueden comunicarse directamente entre sí.

Nivel (tier) frente a capa (layer)
En discusiones sobre arquitectura de tres niveles, la capa a menudo se usa indistintamente, y de manera errónea para referirse a nivel, como en "capa de presentación" o "capa de lógica empresarial". 

No significan lo mismo. Una "capa" se refiere a una división funcional del software, pero un "nivel" se refiere a una división funcional del software que se ejecuta en una infraestructura separada de las otras divisiones. La aplicación Contactos de su teléfono, por ejemplo, es una aplicación de tres capas, pero una aplicación de un solo nivel, porque las tres capas se ejecutan en su teléfono.

La diferencia es importante porque las capas no pueden ofrecer los mismos beneficios que los niveles.



-REST y API-first design

REST es un estilo arquitectónico para servicios web que utiliza HTTP para interactuar con recursos, y el diseño API-first es una filosofía de desarrollo donde las API se diseñan y se documentan exhaustivamente antes de escribir el código para los servicios subyacentes. Un enfoque API-first para el diseño de API REST permite la reutilización de componentes, acelera el desarrollo mediante la colaboración anticipada entre equipos y se puede estandarizar usando formatos como OpenAPI para crear un contrato claro. 
REST (Representational State Transfer)
¿Qué es?Es un conjunto de principios arquitectónicos para el desarrollo de servicios web que permite la comunicación entre diferentes sistemas de manera escalable y eficiente, haciendo un uso extensivo de métodos HTTP como GET, POST, PUT y DELETE. 

Características: 
Sin estado (Stateless): Cada solicitud es independiente y el servidor no guarda información sobre el estado del cliente entre solicitudes. 
Enfoque en recursos: Las operaciones se centran en recursos (como una lista de compras) y se manipulan a través de identificadores uniformes de recursos (URLs). 
Caché: Las respuestas GET pueden ser cacheadas para mejorar el rendimiento, reduciendo la carga del servidor. 

Diseño API-First
¿Qué es?Es una estrategia de desarrollo en la que se define el diseño y los contratos de la API antes de comenzar a codificar la implementación. 

Principios:
Contrato: La API se define mediante un contrato (a menudo usando especificaciones como OpenAPI) que especifica cómo se comportará y qué funciones proporcionará. 
Colaboración: Fomenta la colaboración temprana entre diferentes equipos (frontend, backend) y partes interesadas para definir las necesidades de los consumidores de la API. 
Enfoque en el consumidor: Se prioriza la experiencia del desarrollador (consumidor de la API) al diseñar la interfaz, asegurando que sea intuitiva y fácil de usar. 

Ventajas: 
Desarrollo paralelo: Los equipos pueden desarrollar servicios de forma independiente y simultánea una vez que se establece el contrato de la API, lo que acelera el tiempo de lanzamiento. 
Reutilización: Facilita la creación de API consistentes y reutilizables en múltiples proyectos, lo que reduce el tiempo y esfuerzo. 
Mejora la experiencia del desarrollador: Una buena documentación generada a partir de la especificación OpenAPI mejora la experiencia del desarrollador y permite la automatización del proceso. 

Relación entre ambos
El diseño API-first es un enfoque estratégico que puede ser aplicado al diseño de API REST. Se puede diseñar primero una API RESTful, definiendo su contrato utilizando la especificación OpenAPI, y luego proceder con el desarrollo de la implementación subyacente y los servicios. 

<img width="700" height="382" alt="image" src="https://github.com/user-attachments/assets/be0313c3-eb5c-4f9e-8fa0-8694b6e6228c" />



3. -Lenguajes y tecnologías fundamentales

-html css javascript php mysql que son y para que sirven

HTML es el lenguaje para estructurar contenido web, CSS lo estiliza (diseño), y JavaScript añade interactividad y dinamismo al navegador del usuario. PHP es un lenguaje de programación del lado del servidor para generar contenido dinámico y manejar datos, y MySQL es un sistema de gestión de bases de datos (RDBMS) que se usa con PHP para almacenar y organizar información de manera estructurada. 

HTML (HyperText Markup Language)
Qué es:
Es un lenguaje de marcado que define la estructura y el contenido de una página web. 

Para qué sirve:
Se usa para organizar el contenido en encabezados, párrafos, listas, tablas y otros elementos. 

CSS (Cascading Style Sheets)
Qué es:
Es un lenguaje de hojas de estilo que describe cómo deben presentarse los elementos HTML. 

Para qué sirve:
Sirve para estilizar la página web, controlando el color, la fuente, el diseño y la disposición de los elementos para que se vean atractivos. 

JavaScript
Qué es: Es un lenguaje de programación interpretado. 

Para qué sirve: Se utiliza para añadir interactividad y comportamiento dinámico a las páginas web en el navegador del cliente, como crear menús dinámicos, mostrar mensajes emergentes o interactuar con el usuario. 

PHP (Hypertext Preprocessor
Qué es: Un lenguaje de script del lado del servidor. 

Para qué sirve: Se ejecuta en el servidor para procesar datos, interactuar con bases de datos, generar contenido dinámico y enviar respuestas al navegador del usuario. 

MySQL
Qué es: Un sistema de gestión de bases de datos relacionales (RDBMS). 

Para qué sirve: Se utiliza para almacenar, organizar y manipular datos de manera estructurada, siendo fundamental para aplicaciones web que necesitan guardar y acceder a grandes cantidades de información. 

<img width="282" height="179" alt="image" src="https://github.com/user-attachments/assets/6897be65-bc6c-4e7b-bad0-a4fe0115c23d" />

4.-Control de versiones

-Git y GitHub

Git: La Herramienta de Control de Versiones
¿Qué es?
Git es un software de código abierto que te permite guardar "instantáneas" de tus archivos a lo largo del tiempo, creando un historial del proyecto.

Funcionamiento:
Te ayuda a rastrear los cambios, volver a versiones anteriores si es necesario, y trabajar en diferentes "ramas" de un proyecto sin afectar el código principal. 

¿Cuándo usarlo?
Puedes usar Git de forma individual en tu computadora para llevar un registro detallado de tus cambios. 

<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/9e9b06a3-2d4d-47af-b5a3-b26fc720a2c1" />


-Flujo de trabajo con ramas (branching, merge, pull requests)
Un flujo de trabajo con ramas, merge y pull requests es una práctica común en el desarrollo de software con Git donde los desarrolladores crean ramas separadas (branches) para trabajar en nuevas funciones o correcciones, hacen "pull requests" para proponer que sus cambios se unan (merge) a la rama principal, permitiendo la revisión de código y la colaboración antes de que se integren los cambios en el código base principal. 

Cómo funciona
1. Creación de Ramas (Branching):
Se crea una nueva rama (branch) a partir de la rama principal (normalmente main o master) para trabajar en una nueva característica o una corrección de error de forma aislada. 
Esta nueva rama tiene un nombre descriptivo, como feature/add-new-account-type.

2. Desarrollo y Commits:
Los cambios se realizan y se guardan en la rama recién creada. 
Los cambios se "confirman" (commit) en el repositorio local.

3. Envío a Repositorio Remoto:
La rama y los commits se "empujan" (push) al repositorio remoto, haciendo que estén disponibles para otros colaboradores.

4. Solicitud de Integración (Pull Request):
Un desarrollador solicita que su rama se "combine" (merge) con la rama principal a través de un pull request. 
Este pull request crea una oportunidad para la conversación sobre el código y la revisión del mismo.

5. Revisión y Aprobación:
Otros miembros del equipo revisan el código, discuten los cambios y pueden sugerir modificaciones. 
El proyecto o la rama es aprobado después de la revisión.

6. Combinación (Merge):
Una vez aprobado, el proyecto principal se fusiona con los cambios de la rama de la característica. 
La rama de la característica ya no es necesaria y puede eliminarse.

Beneficios clave

Colaboración Eficiente:
Facilita que múltiples desarrolladores trabajen simultáneamente en diferentes características sin interferir entre sí. 

Aislamiento de Trabajo:
Las nuevas características se desarrollan de forma aislada, lo que reduce el riesgo de introducir errores en el código principal. 

Control de Calidad:
El pull request permite la revisión de código (code review), lo que ayuda a mantener la calidad del código y a compartir conocimientos entre el equipo. 

Historial Limpio:
Las ramas y pull requests ayudan a mantener un historial de commits claro y organizado. 

<img width="342" height="147" alt="image" src="https://github.com/user-attachments/assets/89f34c2e-4e1f-47a4-903b-cfeb04d44182" />

1.-Diseño e implementación del frontend

-Maquetación/Wireframe/Mockup
Una maquetación (o wireframe) es el esqueleto de un diseño que se enfoca en la estructura y el flujo, mientras que un mockup es una representación visual más detallada y estática que incluye la apariencia estética como colores, tipografía e imágenes. Ambas herramientas son cruciales en el proceso de diseño de interfaces de usuario (UI) y experiencia de usuario (UX), siendo el wireframe una etapa inicial de baja fidelidad y el mockup una versión de mayor fidelidad antes de crear un prototipo interactivo. 

Maquetación / Wireframe
Enfoque:
Se centra en la estructura y la disposición de los elementos en una pantalla, sin detalles visuales. 
Propósito:
Definir la funcionalidad, el contenido y la navegación de una interfaz. 

Apariencia:
Es una representación esquemática y de baja fidelidad, a menudo en blanco y negro o con colores neutros. 

Uso:
Es ideal para validar la lógica del diseño y el flujo del usuario en las etapas iniciales de un proyecto. 
Mockup

Enfoque:
Añade el diseño visual y la estética al wireframe. 

Propósito:
Mostrar el aspecto final de la interfaz, incluyendo colores, tipografía, imágenes e iconografía, lo que ayuda a los equipos y clientes a visualizar el producto. 

Apariencia:
Es una representación estática de alta fidelidad, casi idéntica al producto final, pero sin interactividad. 

Uso:
Se utiliza para validar el diseño visual y detectar inconsistencias antes de pasar a prototipos interactivos. 

¿Por qué son importantes?
Claridad:
Permiten que el equipo y los clientes tengan una comprensión clara de la estructura y la apariencia del producto. 

Eficiencia:
Ayudan a detectar errores y realizar cambios en las etapas tempranas del diseño, lo que ahorra tiempo y recursos en comparación con corregir errores en el desarrollo. 

Colaboración:
Facilitan la colaboración entre diseñadores, desarrolladores y partes interesadas, al proporcionar una base visual compartida. 

<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/7c6aacd8-2dde-46f8-adef-4fdf5db1428c" />

-API
Una API (interfaz de programación de aplicaciones) es un conjunto de reglas y definiciones que permite que dos aplicaciones de software diferentes se comuniquen entre sí, actuando como un puente para el intercambio de datos y servicios. Permite a las aplicaciones enviar y recibir información de manera estandarizada, facilitando la creación de aplicaciones más complejas al no tener que desarrollar todas sus funcionalidades desde cero. Por ejemplo, una aplicación de redes sociales usa APIs para obtener tu "feed" de noticias o publicar nuevos contenidos, y una aplicación del clima usa una API para acceder a los datos meteorológicos de otro servicio. 

¿Cómo funcionan las APIs?
1. Solicitud:
Una aplicación (cliente) envía una solicitud a otra aplicación (servidor) a través de la API.

2. Reglas y Formato:
La solicitud debe seguir las reglas y el formato de datos definidos por la API.

3. Respuesta:
El servidor procesa la solicitud y devuelve los datos o ejecuta la acción solicitada. 

<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/6c085b26-26f0-403b-90a4-e3b47b9876e5" />


2.- Diseño e implementación del backend

- **Servidor**

  El servidor es responsable de manejar las peticiones y respuestas HTTP, procesando las solicitudes de los clientes (navegadores, aplicaciones móviles, etc.) y enviando respuestas adecuadas. Además, el servidor se conecta a bases de datos como MySQL, PostgreSQL o MongoDB para consultar, almacenar y modificar datos según lo requiera la aplicación.

- **Manejo de peticiones y respuestas HTTP**

  El protocolo HTTP es la base de la comunicación entre cliente y servidor. El backend recibe solicitudes (GET, POST, PUT, DELETE, etc.) y responde con datos, páginas web o mensajes de error según corresponda.

- **Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)**

  Los servidores suelen interactuar con sistemas de gestión de bases de datos para almacenar información persistente. MySQL y PostgreSQL son bases de datos relacionales, mientras que MongoDB es una base de datos NoSQL orientada a documentos.

## 3.- Bases de datos

- **Modelado de datos y relaciones**

  El modelado de datos consiste en definir cómo se organizan y relacionan los datos dentro de la base de datos, usando tablas (en bases de datos relacionales) o documentos (en bases de datos NoSQL).

- **ORM (Object Relational Mapping)**

  Los ORM permiten mapear objetos del código a tablas de la base de datos, simplificando el acceso y manipulación de datos desde el backend. Ejemplos incluyen Sequelize (Node.js), SQLAlchemy (Python) y Doctrine (PHP).

- **CRUD desde el backend**

  CRUD son las operaciones básicas sobre los datos: Crear, Leer, Actualizar y Eliminar (Create, Read, Update, Delete), que el backend implementa para interactuar con la base de datos.

## 4.- Seguridad básica en aplicaciones web

- **Validación de formularios**

  Antes de procesar datos enviados por el usuario, es fundamental validar los formularios para evitar errores y vulnerabilidades (por ejemplo, inyecciones de código).

- **Autenticación y autorización**

  La autenticación verifica la identidad del usuario (login), mientras que la autorización determina qué acciones puede realizar según sus permisos.

---

## Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional

### 1.- Integración de frontend y backend

- **Interfaz de usuario Frontend**
  
  El frontend presenta la interfaz visual con la que interactúa el usuario y consume los servicios ofrecidos por el backend a través de APIs.

- **Manejo de API**

  La comunicación entre frontend y backend se realiza mediante llamadas a APIs, generalmente siguiendo el estándar REST.

- **Proceso de Solicitud y Respuesta de Backend**

  El frontend envía solicitudes (por ejemplo, para obtener datos o crear registros), el backend las procesa y devuelve las respuestas adecuadas.

### 2.- Almacenamiento en Servidor

- **Tipos de servidores**

  Existen distintos tipos de servidores para hospedar aplicaciones web, como servidores dedicados, VPS (Virtual Private Server), servidores compartidos, y servidores en la nube.

- **Servidores y servicios de hosting**

  Los servicios de hosting como Heroku, AWS, Netlify o Vercel permiten desplegar y mantener aplicaciones web en línea.

- **Proveedores de Servicios de Almacenamiento**

  Empresas como Amazon Web Services, Google Cloud, y Microsoft Azure ofrecen almacenamiento seguro y escalable para aplicaciones web.

### 3.- Optimización y rendimiento

- **Optimización de recursos (imágenes, scripts)**

  Optimizar el tamaño de imágenes, minificar scripts y aplicar buenas prácticas mejora la velocidad de carga y la experiencia del usuario.

- **Despliegue de aplicaciones web**

  El despliegue consiste en publicar la aplicación web en un servidor para que esté accesible a los usuarios.

- **CI/CD básico**

  La integración y entrega continua (CI/CD) automatiza pruebas, integración y despliegue, facilitando la actualización y mantenimiento del proyecto.

- **Documentación del proyecto**

  Documentar el código, la arquitectura y las funcionalidades facilita la colaboración y el mantenimiento del proyecto.


2.-Diseño e implementación del backend

El diseño e implementación del backend implican la creación de la lógica del servidor, las bases de datos y las APIs que hacen funcionar una aplicación web, pero no son visibles para el usuario final. Esto incluye definir la arquitectura del servidor, desarrollar el código en lenguajes como Python o Java, diseñar esquemas de bases de datos, implementar la seguridad, gestionar la escalabilidad y conectar con servicios de terceros, todo ello con el objetivo de procesar solicitudes, almacenar datos y entregar respuestas al frontend. 

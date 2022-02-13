# Módulo 5 - Express

## Clase 19 - Patrones de diseño MVC

- ¿Qué es y para qué sirve un patrón de diseño?
- ¿A qué hace referencia la letra M dentro del patrón MVC?
- ¿Quién interactúa directamente con las vistas?
- ¿Por qué se recomienda implementar un sistema de ruteo en nuestra aplicación?
- ¿Para qué nos sirven las rutas dinámicas?
- Si tuvieras que revisar el código de otra persona, ¿cómo podrías identificar una ruta que recibe parámetros?
- Dentro del cuerpo de código de un controlador, ¿cómo podemos recuperar los parámetros que nos llegan a través de la ruta?
- ¿Vale la pena usar siempre express-generator?
- ¿Cómo hacía el Tiranosaurio Rex para rascarse la frente?

## Clase 20 - Vistas dinámicas con EJS

Motores de plantillas https://expressjs.com/en/resources/template-engines.html

EJS https://ejs.co/

- ¿Qué son los motores de plantillas?
- ¿Para qué usamos los motores de plantillas?
- ¿Por qué usamos EJS como motor de plantillas?
- ¿Qué se entiende por el concepto de “renderización de vistas”?
- ¿Qué nos ayudan a resolver las etiquetas propias de EJS?
- ¿Cómo podemos pasar información desde el controlador a la vista?
- ¿En qué nos ayuda la modularización de vistas?

## Clase 22 - CRUD: Episodio 1

CRUD BREAD https://paul-m-jones.com/post/2008/08/20/bread-not-crud/

## Clase 23 - CRUD: Episodio 2

Multer https://www.npmjs.com/package/multer

- ¿Cuál es la configuración básica, pero necesaria, para que Multer funcione como esperamos?
- Multer: ¿es un middleware de aplicación o es un middleware de ruta?
- ¿Cuáles son los atributos requeridos en el formulario HTML para que Express pueda entender que se desean enviar archivos al servidor?
- ¿Cómo podemos generar que el nombre de archivo que se espera guardar, sea un nombre único y unívoco?
- ¿Tiene Multer la posibilidad de validar si lo que queremos subir es una imagen o un archivo de Excel?

## Clase 25 - Middlewares

Error 404 https://developer.mozilla.org/es/docs/Web/HTTP/Status/404

Código de error https://developer.mozilla.org/es/docs/Web/HTTP/Status

Lista completa de validaciones(readme.md) https://github.com/validatorjs/validator.js#validators

- Entendiendo que un middleware es una función, a parte de los parámetros que representan al request y al response, ¿qué otro parámetro es indispensable que esté presente?
- Para la carpeta de recursos estáticos, en donde se guardan las imágenes y las hojas de estilo de las vistas, ¿se debe usar un middleware global o un middleware de ruta?
- ¿Cuál es la ventaja de usar middlewares de ruta?
- Para usar Express Validator, ¿hay que instalarlo o ya viene por defecto con Express?
- ¿Cuáles son los dos lugares clave en los que se debe usar Express Validator para validar los datos de nuestra aplicación?
- ¿Cómo hacemos para enviar los errores generados en la validación para que se muestren en la vista?
- Estando en la vista, ¿los errores de validación siempre van a estar presentes?

## Clase 26 - Armado de login: session y cookies

Session
- ¿Qué es y para qué sirve?
- ¿Cómo se pueden guardar datos en Session?
- ¿Cómo se pueden recuperar los datos de Session?
- ¿Cuáles son los beneficios de trabajar con Session?
- ¿Cuáles son los escenarios más comunes donde implementar Session?

Cookies
- ¿Qué son y para qué sirven?
- ¿Cómo guardar datos en una cookie?
- ¿Cómo recuperar los datos de una cookie?
- Las cookies: ¿tienen tiempo de expiración?
- Si Session también guarda datos, ¿para qué necesitamos a las cookies?
- ¿Qué datos se deberían guardar en Session y qué datos se deberían guardar en una cookie?

Hashing
- ¿Por qué se hace indispensable encriptar los datos sensibles?
- ¿Cómo podemos generar la encriptación de datos dentro de Node.js?
- Si un dato está encriptado, ¿cómo podemos conocer su contenido?
- Un dato encriptado: ¿se puede desencriptar?

## Para saber más 

Mejores prácticas con Express https://expressjs.com/es/advanced/best-practice-performance.html

bcrypt.js https://eldevsin.site/los-middlewares-en-nodejs/

EJS https://www.digitalocean.com/community/tutorials/how-to-use-ejs-to-template-your-node-application-es

Más templates engines https://openbase.com/categories/js/best-nodejs-html-templating-engine-libraries?orderBy=RECOMMENDED&

Métodos HTTP: hacia una API REST https://otroespacioblog.wordpress.com/2013/05/22/conoce-un-poco-sobre-los-metodos-http-en-rest/

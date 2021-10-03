# 1. La aparición de HTML5/CSS3/JS ha supuesto el nacimiento del desarrollo front-end moderno. (0.75 puntos)

## ¿Cuál es la ventaja del uso de etiquetas semánticas? Nombra y explica al menos 3 de estas ventajas.

Podríamos decir que una de las principales ventajas es la de la accesibilidad, la ventaja de la accesibilidad luego lleva consigo un mejor posicionamiento web y otros elementos, pero la importancia del uso de las etiquetas semánticas es que nosotros con el ojo humano somos capaces de ver la importancia de los elementos de una página web de forma visual, pero los rastreadores no lo son, de esta forma al usar etiquetas semánticas le estamos dando a los rastreadores una estructura de nuestra web, qué es lo importante, cómo está dividida en artículos o secciones etc. y todo esto es muy importante para que estos rastreadores puedan interpretar la información que nuestra web proporciona a personas con problemas de accesibilidad, estas son algunas de las etiquetas que se pueden utilizar:

> <nav> se usa para introducir los links necesarios para la navegación de la web, podría ubicarse por ejemplo en la barra superior.
> <section> Se utiliza para agrupar una sección genérica del documento generalmente por temática.
> <footer> se utiliza para marcar el pie de página del documento


## Cita al menos 3 APIs HTML5 y explica brevemente su funcionalidad.

> Drag & drop, fue creada por Internet Explorer y sirve para subir elementos a una web arrastrando el archivo desde un fichero externo
> Geolocalización, sirve para geolocalizar al usuario a través de su IP
> Websockets, sirven para poder hacer comunicaciones en tiempo real dentro de una web, se pueden utilizar por ejemplo para servicios de mensajería sin tener que actualizar la web para ver los nuevos mensajes.

## Cita qué opción ofrece CSS3 para conseguir que se apliquen diferentes estilos CSS sobre el mismo elemento en su visualización en diferentes dispositivos (diferentes tamaños de pantalla).

> CSS3 introduce las media queries (@media) que sirven para añadir breakpoints e indicarle al elemento como tiene que actuar en función de cual sea por ejemplo el ancho de pantalla.

## Cita al menos 4 de las características principales de TypeScript (importante superset de JavaScript que trataremos en el siguiente capítulo).

> Las variables están tipadas, permite diferenciar el tipo de variables que queremos usar
> Se puede definir si los datos son públicos o privados en una clase
> Se introducen los decorators que permiten añadir funcionalidad de forma dinámica a los objetos
    Simplifica la inyección de dependencias.
      
 # 2. El lenguaje CSS es muy rígido, poco práctico y ordenado a la hora de programar. Para evitar este problema se han creado los preprocesadores CSS, que ofrecen evidentes ventajas (0.5 puntos)

## Cita al menos 2 de estos preprocesadores.

> SASS
> LESS

## Cita al menos 4 ventajas que ofrecen estos preprocesadores.

> Extienden las funcionalidades del CSS común
> Permite tener una organización modular de los estilos
> Reduce el tiempo de crear y mantener el CSS
> Existen muchas librerías y una gran comunidad que trabaja con estos preprocesadores
> Proporciona estructuras avanzadas propias de lenguajes de programación

## Explica brevemente en qué consisten los sourcemaps.

> los sourcemaps son archivos que nos permiten relacionar el código compilado con el código de origen para poder realizar modificaciones o corregir errores.

## Explica qué es un transpilador.

> Es un tipo de compilador que traduce de un lenguaje fuente a otro lenguaje fuente

# 3. El flujo de trabajo profesional en front-end hace indispensable el uso de herramientas como controles de versiones y herramientas de gestión de módulos (0.75 puntos).

## Cita al menos dos sistemas de control de versiones y dos herramientas de gestión de módulos.

>Gestión de versiones:

* Git
* Mercurial
* Subversion

> Gestión de módulos:

* NPM
* Bower
* Jetpack


## Cita y explica al menos 3 comandos de Git.

> git help , muestra los comandos más utilizados de git
> git branch , nos muestra las ramas que hay en nuestro repositorio
> git status , nos indica el estado del repositorio
> git init , crea localmente un repositorio de git

## Cita y explica brevemente las características más definitorias de WebPack.

> Repetible, es decir, garantiza que ese proyecto se puede repetir de igual manera sin importar quien lo hace y dónde lo hace
> Reproducible, es decir, que te permite copiarlo o moverlo a otros sistemas y que se puedan llevar a cabo los mismo pasos para generarlo
> Estándar, es decir, que está alineado con lo que se consideran las mejores prácticas para que los diferentes miembros de un equipo o quien lo vaya a manejar no tengan problema. 
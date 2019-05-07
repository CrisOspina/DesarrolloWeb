# DesarrolloWeb
Curso desarrollo web completado - Platzi

Resumen

* Desarrollo web
** DOM = 
DOM es el acrónimo de Document Object Model o Modelo de 
documento, y es la manera en que se representa el contenido 
del documento, de manera similar a un árbol de nodos.
A continuación, un ejemplo sencillo de la estructura del DOM:
html
	head
		title
		meta
	body
		header
			nav
		section
			article
		footer
		
El **BOM **(Browser Object Model) consiste en el navegador 
de objetos, el historial, la pantalla, la ubicación y el 
documento que son elementos secundarios de la ventana. 
En el nodo del documento está el DOM (Document Object Model),
el modelo de objeto del documento, que representa el 
contenido de la página.		


Algunas de las etiquetas más conocidas y usadas son:

Etiquetas de cabecera (head)
doctype: indica al navegador el tipo de documento que se 
está mostrando.
html: es la etiqueta que envuelve todo el documento

head: es la cabecera del documento y contiene sub etiquetas
que describen al documento o incluyen recursos adicionales.
Etiquetas del cuerpo del documento (body):
article: diferencia partes del contenido que pueden vivir
por sí mismas.

nav: para hacer menús de navegación.

aside: contenido menos relevante, como publicidad, etc.

section: sirve para diferenciar las secciones principales 
del contenido.

header: cabecera del documento.

footer: pie de página del documento.

h1 - h6: títulos de nuestro sitio web.

table: tablas de contenidos, similar a la estructura de 
las hojas de calculo.

ul y ol: listas de items.

div: cualquier división para organizar el contenido.

** Atributos HTML
Los atributos son valores agregados a las etiquetas (tags) 
html que extienden su habilidad o funcionalidad con 
información específica.

A continuación, un ejemplo de los atributos más comunes y 
usados en algunas etiquetas:

Para img:

src: específica la ruta de la imagen que será mostrada a 
través de esta etiqueta. La ruta puede ser absoluta 
(cunado especifica una dirección exacta, incluyendo el 
prefijo http(s) ) o relativa (cuando la referencia a la 
ubicación de la imagen parte de la ubicación del archivo
actual).
alt: indica un texto alternativo que será mostrado en lugar 
de la imagen cuando ésta no pueda ser mostrada.
width: ancho de la imagen en pixeles.
height: alto de la imagen en pixeles.
Para link, en la cabecera head del documento:

rel: indica la relación del recurso con el contenido.
type: indica el tipo de recurso / formato.
href: indica la ubicación (url) del recurso enlazado.
Para meta, ambién en la cabecera head del documento:

charset: indica la tabla de caracteres (utf-8 para 
caracteres latinos) usada en el documento.
Para a:

href: la ubicación o ruta a la que enlaza esta etiqueta de 
ancla. En el caso de querer enlazar a elementos que se 
encuentran dentro del mismo documento, este atributo
debe indicar el valor del atributo ““id”” de ese elemento 
destino del enlace.

/**********************************************************/

Formularios HTML
Los Formularios en html son unidades de información que nos 
permiten recolectar información para enviarlos al 
propietario del website o a un servicio externo. 
Esta formado por dos partes o contextos: una parte 
donde se hace el ingreso y modelación de esos datos 
(en el frontend), y otra parte que se encarga de enviar, 
procesar y almacenar esos datos (en el backend).

Los formularios se crean con la etiqueta form. 
El atributo principal de un formulario es action, 
ya que contiene la ruta a la que serán enviados los 
datos recolectados.

Hay diversos elementos html que permiten la captura o
recolección de datos, aunque generalmente se usan los 
elementos creados con la etiqueta input. Los inputs 
también sirven para crear botones, aunque existe una 
etiqueta especial para ésto llamada button… El atributo 
principal de los inputs es type, que indica el tipo de 
comportamiento o dato que se espera recibir.

Los elementos creados con la etiqueta label muestran 
un texto que se puede asociar con un input para darle 
mayor significado al campo, principalmente cuando no 
se usa el atributo placeholder.		


Para aplicar estilos a los componentes html, lo más común 
y recomendable es hacerlo a través de clases que se asignan
 al elemento html mediante el atributo class.

Un elemento html puede tener varias clases, se deben indicar
en el mismo atributo class pero separadas por un espacio
en blanco.

Al escoger los nombres de clases, debemos tener en cuenta 
que se puedieran aplicar a muchos elementos, o a elementos 
particulares, así que la claridad y precisión en su 
identificación facilitará la contextualización y 
mantenibilidad en el futuro.

Algunos de los estándares más usados para la identificación
 de clases son:

OOCSS
BEM
Component CSS


Hay varias unidades de medida con las que se puede trabajar
 en CSS: %, em, rem, px, pt, fr, vw, vh
Las medidas más comunes y utilizadas son los pixeles. 
Un pixel es la menor unidad homogénea en color que forma 
parte de una imagen digital. Es la unidad más práctica y 
fácil de utilizar y manipular, y es la que utilizaremos 
mayormente en este curso.

Podemos representar un color de 3 formas dentro de CSS:

Palabra clave: red, blue, pink, etc.
Hexadecimales: 0123456789ABCDEF
hls() hlsa()
#000000 = Negro
#FFFFFF = Blanco
Se representan por grupos de 2 -> Red, Green, Blue

#FF0000 = Rojo
#00FF00 = Verde
#0000FF = Azul
Para obtener un color más exacto se utiliza rgb o rgba:

rgb(0, 200, 145)
rgba(0, 50, 70, 0.5) para obtener transparencia
¿Qué es un pixel?
La menor unidad homogenea en color que forma parte de una 
imagen digital.


Inspector de elementos
Para ver y depurar el código de una página html, el 
navegador incluye una herramienta llamada Inspector de
elementos, o simplemente inspector, que abre, en una 
sección de la ventana, una serie de espacios con 
información técnica muy detallada sobre todo lo que 
sucede en el DOM, incluídos los estilos que tienen 
aplicados cada uno de los elementos del html.

La mayoría de los navegadores incluye algún tipo de 
Inspector, en el curso usamos Google Chrome, pero la 
misma herramienta (o similar) la encuentras en Firefox, 
Opera, Edge, etc.

Utilizando el Inspector podemos hacer modificaciones 
(temporales) manualmente en el html de cualquier sitio web, 
consultar sus estilos y recursos enlazados, hacer pruebas 
en tiempo real con JavaSsript, monitorear variables o 
eventos entre muchas otras tareas útiles para cualquier 
desarrollador.


Tipos de textos personalizados
Los tipos de texto, también conocidos como tipos de letras 
o fuentes, son el conjunto de diseños tipográficos que 
representan a cada una de las letras y los caracteres 
gráficos en el documento. Su nombre correcto es tipografía. 
Los diferentes tipos de fuente están basados en archivos 
que existen en cada sistema operativo.

Algunos ejemplos de tipos de texto o fuentes, son:

Arial
Times New Roman
Verdana
DeJaVu
Lato
OpenSans
Roboto
CSS permite utilizar fuentes diferentes a las disponibles 
en el sistema operativo del cliente, mediante la importación 
o el enlace a archivos de fuentes externas. Las más usadas 
son las que están disponibles a través del sitio web de 
Google Fonts.

Al definir el tipo de texto asociado a una clase css con 
la propioedad font-family indicamos al navegador, que 
debe intentar usar esa fuente en particular para darle 
la apariencia tipográfica a los textos de ese elemento html


Diferencias de las propiedades padding y margin:

Margin es el margen que hay desde un elemento hasta los 
que tenga al lado.
Padding es el espacio que hay en un contenedor entre el 
contenido y los bordes del contenedor.

/**********************************************************/

El modelo de caja es un concepto teórico de css que representa a cada 
elemento html en base sus propiedades de: margin, border, padding y dimensiones (alto y ancho).
Para visualizar un elemento html en su representación como modelo de 
caja debemos irnos a la parte baja de la sección styles del inspector 
de elementos, o en la sección llamada Computed.

En el modelo de caja, el ancho total de un elemento html equivale a la 
sumatoria de los valores de: width, padding-left, padding-right, border-left-width, border-right-width. De manera similar aplica para el alto total de cada elemento. Aunque margin-left y margin-right, forman parte del modelo de caja, no se incluyen para el calculo del ancho total.

Con la propiedad box-sizing, y en particular con el valor border-box 
de esta propiedad, podemos modificar el comportamiento del modelo de 
caja para que nuestro elemento nunca supere el tamaño máximo que le 
hayamos definido en width y height. Esta es la opción recomendad para trabajar.

/**********************************************************/


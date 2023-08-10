# Guía para la gestión del sitio web de Némesis

El presente repositorio contiene los archivos necesarios para modificar y actualizar la página web de la Revista Némesis. La estructura es la siguiente:

En la capa inicial se encuentran los documentos asociados al inicio de la página, es decir, las plantillas .qmd de cada sección dispuesta en la barra de navegación superior. Además, se encuentra el yml que renderiza el archivo html que luego se publica en la página, el archivo css que le da forma a la página y carpetas de trabajo.

Las carpetas son las siguientes:

-   `docs` : Contiene los archivos necesarios para diseñar el documento html en el que se basa la página web. Su contenido se hace de manera automática una vez que se manda a renderizar el proyecto.
-   `images`: Contiene todas las imágenes que se publican en la página.
-   `docx_pdf`: Contiene los documentos en formato word o pdf que se publican en la página, como anexos de convocatorias, escritos, entre otras.
-   `product`: Subsección que contiene las plantillas .qmd que despliegan las listas de las distintas publicaciones que se alojan en la barra lateral de la página. Dentro de la carpeta, cada tipo de producto tiene su propia carpeta en la que se distribuyen los escritos publicados.
-   `recents`: Contiene las plantillas .qmd de cada noticia u actividad de la Revista que se publica en la web.

Asimismo, en la capa inicial se alojan archivos de soporte de la página como `404.qmd` que muestra la plantilla de error de navegación y `styles.css` que contiene la configuración estética de la web.

### Códigos de .qmd

Los archivos *.qmd* que están en las carpetas `product` y `recents` están codificados de tal manera de favorecer el orden y la posibilidad de encontrar estos archivos. A continuación se presenta el diccionario de cada una de esas plantillas.

##### recents

-   `new_02`: Némesis te invita al nuevo seminario internacional de OLES
-   `new_01`: ¡Némesis inaugura su nueva página web!

##### comentarios

-   `com_bib_01`: La era de la Farsa de Rodrigo Baño.
-   `com_bib_02`: Desobeder de Federic Gros.
-   `com_bib_03`: Chavs. La demonización de la clase obrera de Jon Owen.
-   `com_bib_04`: El misterio de los kibbutz de Ran Abramitzky.
-   `com_bib_05`: La ideología de la competencia de Marinela Chaui.
-   `com_bib_06`: Contra el fasciscmo de Humberto Eco.
-   `com_bib_07`: De la "regeneración del pueblo" a la huelga general de Sergio Grez.

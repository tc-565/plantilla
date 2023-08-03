# Panel-note (Título de la nota)

Note que al digitar `[toc]` en una línea aparte, es posible insertar una tabla de contenidos únicamente para los títulos de nivel 2 (##).

[toc]

## Acerca de
Este es un `panelnote`. Su función es elevar una nota escrita en Markdown para que sea directamente visible en un objeto `unit`.

Se crea con un directorio `panelnote`, con ubicado dentro de un objeto `unit`, que a su vez se ubica dentro de un `Topic` como `topic-yy-nombre`, con ubicación en la raíz del sitio web.

Recuerde que dentro del directorio `topic-yy-nombre` debe haber un archivo topic.md que contenga el título y descripción del tópico.

## Estructura y ubicación
* topic-yy-nombre
	* topic.md
 	* topic.png (opcional)
 	* unit
  		* topic.md
    	* **panelnote**
     		* note.md
       		* note.png (opcional)
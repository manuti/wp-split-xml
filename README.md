wp-split-xml
============

copia del script python para dividir los xml de WordPress antes de importarlos

Visto en:
http://lamiradadelreplicante.com/2014/02/08/como-dividir-los-archivos-de-importacion-xml-en-wordpress/

y este a su vez de Eraac:
http://wordpress.org/support/topic/wxr-file-splitter


El archivo se cuarda como splitter.py se le dan permisos de ejecución, en las propiedades del archivo.

Finalmente para dividir nuestro archivo xml, tan solo tenemos que ejecutar esto en la terminal

./splitter.py nombre_archivo.xml n

donde n, es el número de veces que lo queréis dividir, por ej:

./splitter.py lamiradadelreplicante.xml 8

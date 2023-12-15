# demo-iframe
Embeber un mapa de Mapas Córdoba en tu sitio web


1) Identificar el mapa que te interesa incrustar en tu sitio web
Ingresar a Mapas Córdoba e identificar el id del mapa, que es el número que se encuentra en la URL. Por ejemplo, en la URL https://mapascordoba.gob.ar/viewer/mapa/15 del mapa de Catastro, el id es 15.

2) Usar el código que se muestra a continuación
Copiar el código e incorporar la dirección (URL) con el id del mapa que se desea incrustar
```:html
  <iframe
    src="https://mapascordoba.gob.ar/viewer/embed/mapa/15"
    width="800"
    height="600"
    >
  </iframe>
```


3)  Agregar el componente iFrame en tu página
Embeber el mapa en tu página web usando la etiqueta (tag) HTML iframe, dentro de la página contenedora. Podés asignar atributos (valores) de visualización del mapa, por ejemplo: ancho (width) y alto (height), bordes (frameborder), entre muchos más. Consultá otros atributos para mejorar tu marco en este enlace (https://developer.mozilla.org/es/docs/Web/HTML/Element/iframe)

![image](https://github.com/IDECOR/demo-iframe/assets/58694347/f058776a-8680-4d00-ac6b-1a2147517f05)


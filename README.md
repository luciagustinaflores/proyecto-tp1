#Proyecto TP1 Frontend#

html-css: 
    - div principal: para que el diseño pudiera tener forma de tarjeta, se tomó la decisión de envolver el contenido del body en un div.
    - sections: en total, contando el header, son 4 sections: el header, el textarea, las tarjetas de colores con los resultados y el porcentaje de cada letra al final. 
    - styles generales: las variables encierran los colores, el * es simplemente un reseteo del margin, padding y box-sizing, y el body contiene algunos style generales: color de fondo, fuente tipográfica, ajustes de display.
    - header: no se incluyó un navbar debido al que diseño, incluso responsive en pantallas más pequeñas, parece mantenerse en la totalidad del vh para evitar el scroll al usuario. hablamos de una experiencia de usuario para el propósito del sitio. al header se le incluyó un div contenedor del nombre de la app/marca con el logo, encerrado dentro de otro div con el btn futuro para cambiar theme, de esta forma la estructura queda organizada y cumple con el diseño propuesto. fuera de los divs se encuentra el h1. 
    - #text-input: style para el input textarea y en un div los checkbox separandolos del p, mismo caso que en el header, permitiendo mejor distribución de los elementos. checkbox para las opciones de "exclude spaces" y "set character limit", textarea para que el usuario inserte su texto. 
    - #cards se utilizó una ul, estilando cada li para que coincida con el color de cada tarjeta y tenga forma de esta.
    - #total-each: se decidió utilizar la etiqueta "progress", mostrando de manera prolija los porcentajes brindados por el diseño referente y quitándole el style predeterminado con "-webkit-appearance" para poder brindar el style personalizado. el btn .see-more pretendía extender brevemente el listado de caracteres, aunque está la opción de reemplazarlo por un checkbox. aun trabajando en eso. 
    
    NUEVA ENTRADA 01/06/2026: 
    - #total-each: se eliminó "fila-letra-hidden", el diseño cumple con la referencia, más adelante se continuará trabajando para inluirle js y el dinamismo del mismo. además, se modificó el btn see-more, se creó la flecha con una caja vacía de css, rotándola y solo "pintando" 2 de sus bordes para que simule una flecha.

html-css. 

creación de este archivo: 31-05-2026.
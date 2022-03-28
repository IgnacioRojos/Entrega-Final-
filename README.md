La pagina web contiene 5 vistas, (index, nosotros, dudas, contacto) se modificaron con bootstrap
la vista servicios se modifico con css nativo aplicado grid y flex. Cada página tiene AOS en el footer,
todas tienen el mismo color de fondo, en el archivo de scss "contenido index" esta aplicado la función
que hace un degrade con el color, esa linea de codigo modifica a todas las views.
Hay archivos scss para cada vista y cada vista tiene dos archivos(uno de la vista pc y otro con la vista mobile).
Con respecto a la vista servicios la barra de navegacion cambia ya que no pude utilizar bootstrap.
Esta barra de navegacion tiene un submenú que al desplegarlo redirecciona a ciertas partes de las vistas dudas,
nosotros y servicios.Tuve problemas para hacer el submenú con bootstrap.El logo redirecciona al inicio desde cualquier vista.

INDEX:
se le aplico bootstrap, tiene un animación en la imagen de decoracion, es la que esta al lado del texto presentación.
Las opiniones tienen aplicadas un mapa que modifica colores.

SERVICIOS:
utilize css para esta vista, tiene una animación en el cuadro de la derecha, cada cuadro tiene aplicado o un borde o 
un degrade de color, la barra de navegacion tiene un submenú que redirecciona.

NOSOTROS:
aplicamos bootstrap, los textos quedaron del lado izquierdo. Hay un courrusel con tres imagenes de muestra y abajo 
hay un video de como trabajamos que le aplique un borde para destacarlo.

CONTACTO:
aplique bootstrap, hay cuatro fotos, las dos primeras de la izquierda(logo telefono y gmail) tiene una tarjeta sacada
de bootstrap, las de la derecha(logo de trasferencia y mercadopago) tienen aplicadas una transicion que se agrandan en 
un tiempo de 2 segundos, los titulos de estos logos tienen aplicados un mixin. 
Abajo se encuentra un titulo y el mapa donde esta ubicado el local.

DUDAS:
tiene bootstrap, a la izquierda hay un formulario donde podes dejar tus dudas, antes tenia un borde amarillo pero
se lo saque. a la derecha se encuentra una lista con preguntas frecuentes(tienen aplicada un mapa que modifica colores).
Las preguntas también tienen AOS.
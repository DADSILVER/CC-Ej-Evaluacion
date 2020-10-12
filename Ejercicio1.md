# Ejercicio 1

### Buscar una aplicación de ejemplo, preferiblemente propia, y deducir qué patrón es el que usa. ¿Qué habría que hacer para evolucionar a un patrón tipo microservicios?


-	La aplicación que he escogido ha sido mi TFG, un programa basado en usar la realidad virtual para simular el montaje de un motor (cuál sea) con la mayor realidad posible. El patrón que sigue la aplicación es monolítico, ya que aunque esta tiene dos partes (una de ensamblaje de un motor y otra de un caso prático de como darle valores al motor para su funcionamiento) se decidio que fueran en un único programa sin separarlas.
	

![Imagen](Img/TFG.png)


-	Para que esta aplicación evolucionase a un patrón de microservicios, habria que dividir las funcionalidades en partes mas pequeñas pensando en cuales se pueden ejecutar de forma asíncrona. En primer lugar dividira las dos partes principales, el ensamblaje del motor, y las praácticas de medición de datos. En segundo luegar la parte de ensamblaje se puede dividir mas aun ya que tiene distintos modos dentro de la aplicación (modo práctica, modo normal y modo examen). A partir de tener las funcionalidades divididas se puede pensar en añadir otras, por ejemplo poder descargar modelos de motores nuevos para usarlos en la parte de ensamblaje.








# BR14NG4MER.github.io
# EL GIROSCOPIO

<h1> ¿QUE ES?

El giroscopio o giróscopo es un elemento mecánico que se usa para poder conocer el horizonte, ya que siempre mantendrá una orientación perpendicular al plano o la superficie de la tierra, lo cual permite conocer y medir la orientación de un elemento, dispositivo o vehículo respecto al espacio.d

![](https://upload.wikimedia.org/wikipedia/commons/c/ca/3D_Gyroscope-es.png)

Entre los usos más comunes que se les da hoy en día a los giroscopios están el del horizonte artificial de los aviones u barcos, además de estar presentes en dispositivos electrónicos como mandos, wearables, móviles o tabletas de última generación.

![](https://i.blogs.es/ac1f6e/giros/840_560.jpg)

<h2> ¿PARA QUE SIRVE?

El giroscopio tiene la tarea de identificar la orientación de un dispositivo en un espacio cualquiera, lo cual es esencial para conocer el estado en el plano del dispositivo y lo cual, si se une a otros datos como los de un acelerómetro o un sensor GPS permiten situar un objeto y conocer todos sus movimientos de forma precisa.

En el caso de los móviles u otros dispositivos electrónicos, en vez de usarse giroscopios tradicionales, se usan giroscopios electrónicos que miden las rotaciones para así saber hacia donde se ha movido el dispositivo en vez de tener un horizonte artificial en su interior, razón por la que a veces es necesario calibrarlos antes de usarlos en aplicaciones que requieren mucha precisión como una brújula. Entre los usos que se le dan están el de rotar la pantalla al girar el móvil, conocer a la hora de hacer fotos panorámicas hacia donde está apuntando el móvil para realizarlas correctamente o usar aplicaciones como la brújula, que entre otras cosas también ofrece en algunas modelos funciones como el horizonte artificial o nivel.
![](https://www.5hertz.com/image/catalog/tutoriales/arduino/tutorial2/Giros1.jpg)

<h2> ESPECIFICACIONES

Hay muchas especificaciones a tener en cuenta al seleccionar un giroscopio. Aquí están algunos de los más importantes los:  

### 3.1 Alcance.

El rango de medición, o rango de escala completa, es la velocidad angular máxima que el giroscopio puede leer.  

### 3.2 Sensibilidad.

La sensibilidad se mide en mV por grado por segundo ( mV / ° / s ) . No deje que la dimensión extraña de este valor te asuste . Se determina la cantidad de los cambios de voltaje para una velocidad angular dada. Por ejemplo, si se especifica un giroscopio con una sensibilidad de 30 mV / ° / s y se ve un cambio de 300 mV en la salida, esto quiere decir que el giroscopio rota a 10 º / s.
![](http://www.5hertz.com/image/catalog/tutoriales/arduino/tutorial2/giros5.jpg)
### 3.3 Off set.

Al igual que con cualquier sensor, los valores que son medidos contendrán cierta cantidad de error o corrimiento. Usted puede ver el corrimiento midiendo la salida cuando el giroscopio se encuentre estático. Aunque se podría pensar que se vería 0°/s, siempre se verá un ligero error distinto de cero en la salida. Estos errores son a veces llamados desplazamiento de la polarización. La temperatura del sensor afecta en gran medida el error. Para ayudar a minimizar el origen de este error, la mayoría de los giroscopios han incorporado un sensor de temperatura. Por lo tanto , usted es capaz de leer la temperatura del sensor y corregir cualquier temperatura o cambios dependientes. Con el fin de corregir estos errores, el giróscopo debe ser calibrado. Esto se hace generalmente al mantener el giroscopio quieto y reduciendo a cero de todas las lecturas en el código.

En la siguiente tabla se encuentran varios modelos de giroscopios, así como sus especificaciones.
![](/Imagenes/tablagiroscopio.png)

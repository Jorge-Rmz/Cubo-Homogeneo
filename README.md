# Cubo-Homogeneo

#### En la siguiente imagen se puede observar las librerías que se utilizará, vemos aquí en la clase main el tamaño de la pantalla.
![fIGURA 8](https://user-images.githubusercontent.com/71052252/143891468-39858743-4a8d-4d89-ae21-01ff7e0662d5.png)

#### En la siguiente imagen vemos las líneas de código de lo que hará el programa cuando finalice, con la línea animator.stop se detendrá la animación y el siguiente código se cerrará la ventana. Y las siguientes líneas nos sirve para centrar la ventana y hacerla visible.
![fIGURA 9](https://user-images.githubusercontent.com/71052252/143891472-62b8fa4c-977c-4ac9-a0e1-7ca0e2954a07.png)

#### En el método init se inicializa la variable gl que nos servirá para dibujar las figuras, y también asignamos las coordenadas en donde se podrá dibujar las figuras.
![fIGURA 10](https://user-images.githubusercontent.com/71052252/143891473-32ab1d81-b5c8-4c83-b162-be5fcaf0eac2.png)

#### En la función reshape se pasa por parámetros de tipo int, en el interior de la función se determinan el tamaño que tendrá la ventana donde se mostrará las figuras, se inicializa la matriz actual con los valores de la matriz identidad de orden 4*4, también observamos las líneas de código para que podamos ver la figura a una vista simétrica, este valor se multiplica por la matriz actual.
![fIGURA 11](https://user-images.githubusercontent.com/71052252/143891475-bf0ab1a2-f23a-4b7b-93ad-0d6542974a84.png)

#### En la siguiente función se muestra el código para dibujar las partes de la figura 3D. Primero se muestra la parte de debajo de la figura 3D, primero se muestra el código que hará que la figura dibujada tenga un color, este tipo de color lo tendrá todos los lados de nuestra figura. Después se muestra el código para dibujar cada uno de los vértices para hacer cada uno de las caras que tendrá nuestro cubo.
![fIGURA 12](https://user-images.githubusercontent.com/71052252/143891476-0d8125c3-d37b-4651-8819-dc0b5073982f.png)

#### Aquí vemos el código para dibujar la parte izquierda y superior del cubo, como en todas las caras que dibujamos primero se pone el color que tendrá dicha cara, el cual va ser de un solo color en todos los lados.
![fIGURA 13](https://user-images.githubusercontent.com/71052252/143891477-d54636e8-705f-45f4-97af-caa2eeeb90fc.png)

# Resultados
#### Al ejecutarlo nos muestra la siguiente figura, como podemos observar dicha figura es un cubo el cual solo tiene un color.
![fIGURA 14](https://user-images.githubusercontent.com/71052252/143891478-c1938c63-e052-468f-9d1f-a298acb34b88.png)

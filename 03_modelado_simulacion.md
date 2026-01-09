En cuanto a simulación: el único sistema móvil que tenemos en el robot son las seis patas. Añado un gif de su funcionamiento.

![Movimiento pata](./images/leg_movement.gif)


Como podemos observar se trata de una pata con dos grados de libertad, lo que nos permite realizar giros y cambiar la altura del extremo más cercano al piso.

Hemos elegido este diseño porque es un diseño simple que nos permite moverlo en cualquier dirección.

Para el movimiento hemos decidido hacer una marcha con forma de triángulo. Es decir:

El robot inicia con tres patas levantadas.

1. Las mueve hacia delante.
2. Baja las patas.
3. Levanta las otras tres
4. Mueve las tres primeras hacia su posición inicial minetras mueve las otras tres hacia delante.
5. Baja las tres patas subidas
6. Levanta las tres iniciales
7. Y mueve las otras tres hacia su posición inicial
8. Repite.
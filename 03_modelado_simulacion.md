En cuanto a simulación: el único sistema móvil que tenemos en el robot son las seis patas. Añado un gif de su funcionamiento.

[Movimiento pata](./images/leg_movement.gif)


Como podemos observar se trata de una pata con dos grados de libertad, lo que nos permite realizar giros y cambiar la altura del extremo más cercano al piso.

Hemos elegido este diseño porque es un diseño simple que nos permite moverlo en cualquier dirección.

Para el movimiento hemos decidido hacer una marcha con forma de triángulo. Es decir:

- Levanta 3 de las 6 patas.
- Gira esas tres patas.
- Baja las patas.
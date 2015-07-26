# Eventi

Tipi di parametri:
 * string
 * number
 * vector3
  * x (number)
  * y (number)
  * z (number)
 * vector4
  * x (number)
  * y (number)
  * z (number)
  * w (number)
 * identity
  * type (number)
  * instance (number)

Tutti gli eventi hanno i parametri seguenti:
 * sender.id (identity)
 * sender.name (string)

## jump
> Quando un player salta

Parametri
  * sender = Chi sta saltando
  * position (vector3)
  * direction (vector4)

## sit
> quando un player si sitta

Parametri
 * sender = Chi si siede
 * position (vector3)
 * direction (vector4)

## move
> quando un player si muove

Parametri
 * sender = Chi si muove
 * position (vector3)
 * direction (vector4)








# Eventi

Tipi di parametri:
 * string
 * number
 * vector3 { x, y, z }
 * vector4 { x, y, z, w }
 * identity { type, instance }

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








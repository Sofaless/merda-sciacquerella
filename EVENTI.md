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
 * entity
  * id (identity)
  * name (string)

Tutti gli eventi hanno i parametri seguenti:
 * sender (entity)

## jump
> Quando un player salta

Parametri
  * sender (entity) = Chi sta saltando
  * position (vector3)
  * direction (vector4)

## sit
> quando un player si sitta

Parametri
 * sender (entity) = Chi si siede
 * position (vector3)
 * direction (vector4)

## move
> quando un player si muove

Parametri
 * sender (entity) = Chi si muove
 * position (vector3)
 * direction (vector4)

## start_attack
> Quando A inizia ad attaccare B

Parametri
 * sender (entity) = Chi sta attaccando
 * target (entity) = Chi viene attaccato







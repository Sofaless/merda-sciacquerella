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

-----------------------------------------------------------------------------------

## gesture
> AO Emotes

Parametri
 * sender (entity)
 * gesture (string)
  * wave
  * salute
  * etc ...

## jump
> Quando un player salta

Parametri
  * sender (entity)
  * position (vector3)
  * direction (vector4)

## move
> quando un player si muove

Parametri
 * sender (entity)
 * position (vector3)
 * direction (vector4)

## sit
> quando un player si sitta

Parametri
 * sender (entity)
 * position (vector3)
 * direction (vector4)

## start_attack
> Quando A inizia ad attaccare B

Parametri
 * sender (entity) = Chi sta attaccando
 * target (entity) = Chi viene attaccato


## stand - quando qualcuno si alza

## team_join - Qualcuno entra in team
## team_leave - Qualcuno esce dal team
## team_invite - Ti hanno invitato in team
## team_kick - Qualcuno è stato kickato
## team_changed - Il team è cambiato
## team_leader - Cambia il team leader

## chat_connect - Connesso al server di chat
## chat_disconnect - Disconnesso dal server di chat
## chat_priv_message - Qualcuno ti manda un msg privato

## game_connected - Connesso al server di gioco
## game_disconnected - Disconnesso dal server di gioco
## game_charinplay - Il personaggio è effettivamente in gioco

## skill_available - Skill bloccato (es. special or abilities)
## skill_disabled - Skill sbloccata (es. special or abilities)
## perk_available
## perk_disabled

## cast_start - Inizia cast nano
## cast_finish - Finisce il cast del nano (non include il recharge)
## cast_interrupt - Cast interrotto
## cast_available - Nano recharge terminato



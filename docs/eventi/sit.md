# Name

	sit

# Description

This event is fired when a player sits down.

# Params

- sender (entity)
- position (vector3)
- direction (vector4)

# Example

	game.on('sit', function(e) 
	{
		log('Player %s sits down', e.sender.name);
	});

# Color 
##### tints the node elements using its assigned color.
### modulate = Color8(R,G,B,Alpha)


```sh
extends KinematicBody2D

onready var animation_player = $Animation_world14a
onready var timer = $ResetTimer

export var reset_time : float = 1.0

onready var reset_position = global_position

var velocity = Vector2()
var is_triggered  = false

func _ready():
	set_physics_process(false)
	
	modulate = Color8(210,180,140,255)
```

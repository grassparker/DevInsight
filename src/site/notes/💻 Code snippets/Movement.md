---
{"dg-publish":true,"permalink":"/code-snippets/movement/"}
---



#Mechanics #Development 

```gd
var direction: Vector2 = Vector2(0,0)
var speed: int = 5

func _physics_process(delta: float) -> void:
	direction = Input.get_vector("Left", "Right", "Up", "Down")
		
	position += direction * speed
```

**Need to set the keybinds first**
**Mobile has a different version**

#Bug Sometimes the gd script could be attached to the wrong obejct, so always check where the script is attached.

---
## Updates
1. [[📋 Git/18th Jan, 2026\|18th Jan, 2026]]
2. 
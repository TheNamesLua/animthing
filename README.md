# Ez-Animation-Loader V2.0
Easily load, play, and stop animations.


# 2.0 Features
- You can now adjust an animations speed
- Cleaned up code

This is a basic module that I made to clean up your code when importing, loading, and stopping animations easier.

!Avoid having duplicate animation names!



# How to import Ez Animation Loader

```lua
local animationLoader = require(game.ReplicatedStorage.EzAnimationLoader)
```


# How to use Ez Animation Loader

```lua
-- Playing Animation:
animationLoader:PlayAnimation(CharacterObject, AnimationObject)

-- Example:
animationLoader:PlayAnimation(char,script.Animation)  


-- Stopping Animation:
animationLoader:StopAnimation(CharacterObject, AnimationObject)

-- Example:
animationLoader:StopAnimation(char,script.Animation)  


-- Adjusting Animation Speed:
animationLoader:ChangeSpeed(CharacterObject, AnimationObject, Speed)

-- Example:
animationLoader:ChangeSpeed(char,script.Animation, 2)  
```
# Extra features
You can parse a third argument in any of the functions.
Example:
animationLoader:PlayAnimation(char,script.Animation,true)
This will print:
"Starting animation ANIMATIONNAME for PLAYERNAME"

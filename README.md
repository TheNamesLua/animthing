# Ez-Animation-Loader V2.0
Easily load, play, and stop animations.

This is a basic module that I made to clean up your code when importing, loading, and stopping animations easier.



# How to import Ez Animation Loader

```lua
local animationLoader = require(game.ReplicatedStorage.EzAnims)
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
```

# Ez-Animation-Loader
Easily load, play, and stop animations.

This is a basic module that I made to clean up your code when importing, loading, and stopping animations easier.



# How to import Ez Animation Loader

```lua
local animationLoader = require(game.ReplicatedStorage.EzAnims)
```


# How to use Ez Animation Loader

```lua
-- Playing Animation:
animationLoader:PlayAnimation(CharacterObject, AnimationObject, ShowDebug)

-- Example:
animationLoader:PlayAnimation(char,script.Animation,true)  


-- Stopping Animation:
animationLoader:StopAnimation(CharacterObject, AnimationObject, ShowDebug)

-- Example:
animationLoader:StopAnimation(char,script.Animation,true)  
```

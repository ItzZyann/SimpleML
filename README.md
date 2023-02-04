**Geometry Dash ModLoader**

- SimpleML is a GD Mod loader for android, but it just only have few or small headers.
- Its your choice whether you gonna continue to build the cocos2dx headers or not.

Edit the classes.dex to this:
Find geometryjump.dex or smail first.

```xml
.line 69
const-string v0, "fmod"

invoke-static {v0}, Ljava/lang/System;->loadLibrary(Ljava/lang/String;)V

.line 70
const-string v0, "cocos2dcpp"

invoke-static {v0}, Ljava/lang/System;->loadLibrary(Ljava/lang/String;)V

.line 70
const-string v0, "dobby"

invoke-static {v0}, Ljava/lang/System;->loadLibrary(Ljava/lang/String;)V

.line 70
const-string v0, "simple_gdml"

invoke-static {v0}, Ljava/lang/System;->loadLibrary(Ljava/lang/String;)V
```

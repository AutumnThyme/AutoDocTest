# Input## Methods
|Function|Returns|Description|
|---|---|---|
|GetKeyName(key : String)|String|Gets the key name the player assigned to the key setting|
|GetKeyHold(key : String)|Boolean|Returns true if the key is being held down|
|GetKeyDown(key : String)|Boolean|Returns true if the key was pressed down this frame|
|GetKeyUp(key : String)|Boolean|Returns true if the key was released this frame|
|GetMouseAim()|CustomLogicVector3Builtin|Returns the position the player is aiming at|
|GetCursorAimDirection()|CustomLogicVector3Builtin|Returns the ray the player is aiming at|
|GetMouseSpeed()|CustomLogicVector3Builtin|Returns the speed of the mouse|
|GetMousePosition()|CustomLogicVector3Builtin|Returns the position of the mouse|
|GetScreenDimensions()|CustomLogicVector3Builtin|Returns the dimensions of the screen|
|SetKeyDefaultEnabled(key : String, enabled : Boolean)|Void|Sets whether the key is enabled by default|
|SetKeyHold(key : String, enabled : Boolean)|Void|Sets whether the key is being held down|

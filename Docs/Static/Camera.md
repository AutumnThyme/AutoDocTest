# Camera## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|IsManual|Boolean|False|Is camera in manual mode.|
|Position|CustomLogicVector3Builtin|False|Position of the camera.|
|Rotation|CustomLogicVector3Builtin|False|Rotation of the camera.|
|Velocity|CustomLogicVector3Builtin|False|Velocity of the camera.|
|FOV|Single|False|Field of view of the camera.|
|CameraMode|String|False|Current camera mode.|
|Forward|CustomLogicVector3Builtin|False|Forward vector of the camera.|
|Right|CustomLogicVector3Builtin|False|Right vector of the camera.|
|Up|CustomLogicVector3Builtin|False|Up vector of the camera.|
|FollowDistance|Single|False|Distance from the camera to the character.|
## Methods
|Function|Returns|Description|
|---|---|---|
|SetManual(manual : Boolean)|Void|Sets the camera manual mode. If true, camera will only be controlled by custom logic. If false, camera will follow the spawned or spectated player and read input.|
|SetPosition(position : CustomLogicVector3Builtin)|Void|Sets camera position.|
|SetRotation(rotation : CustomLogicVector3Builtin)|Void|Sets camera rotation.|
|SetVelocity(velocity : CustomLogicVector3Builtin)|Void|Sets camera velocity.|
|LookAt(position : CustomLogicVector3Builtin)|Void|Sets the camera forward direction such that it is looking at a world position.|
|SetFOV(fov : Single)|Void|Sets the camera field of view. Use 0 to use the default field of view.|
|SetCameraMode(mode : String)|Void|Forces the player to use a certain camera mode, taking priority over their camera setting. Accepted values are TPS, Original, FPS.|
|ResetDistance()|Void|Resets the follow distance to player's settings.|
|ResetCameraMode()|Void|Resets the camera mode to player's settings.|

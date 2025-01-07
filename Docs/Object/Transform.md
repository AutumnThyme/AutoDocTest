# Transform## Initialization
```csharp
```
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|Position|CustomLogicVector3Builtin|False|Gets or sets the position of the transform.|
|LocalPosition|CustomLogicVector3Builtin|False|Gets or sets the local position of the transform.|
|Rotation|CustomLogicVector3Builtin|False|Gets or sets the rotation of the transform.|
|LocalRotation|CustomLogicVector3Builtin|False|Gets or sets the local rotation of the transform.|
|QuaternionRotation|CustomLogicQuaternionBuiltin|False|Gets or sets the quaternion rotation of the transform.|
|QuaternionLocalRotation|CustomLogicQuaternionBuiltin|False|Gets or sets the quaternion local rotation of the transform.|
|Scale|CustomLogicVector3Builtin|False|Gets or sets the scale of the transform.|
|Forward|CustomLogicVector3Builtin|False|Gets the forward vector of the transform.|
|Up|CustomLogicVector3Builtin|False|Gets the up vector of the transform.|
|Right|CustomLogicVector3Builtin|False|Gets the right vector of the transform.|
## Methods
|Function|Returns|Description|
|---|---|---|
|GetTransform(name : String)|CustomLogicTransformBuiltin|Gets the transform of the specified child.|
|GetTransforms()|CustomLogicListBuiltin|Gets all child transforms.|
|PlayAnimation(anim : String, fade : Single = 0.1)|Void|Plays the specified animation.|
|GetAnimationLength(anim : String)|Single|Gets the length of the specified animation.|
|PlaySound()|Void|Plays the sound.|
|StopSound()|Void|Stops the sound.|
|ToggleParticle(enabled : Boolean)|Void|Toggles the particle system.|
|InverseTransformDirection(direction : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|InverseTransformPoint(point : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|TransformDirection(direction : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|TransformPoint(point : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|Rotate(rotation : CustomLogicVector3Builtin)|Void||
|RotateAround(point : CustomLogicVector3Builtin, axis : CustomLogicVector3Builtin, angle : Single)|Void||
|LookAt(target : CustomLogicVector3Builtin)|Void||
|SetRenderersEnabled(enabled : Boolean)|Void|Sets the enabled state of all child renderers.|

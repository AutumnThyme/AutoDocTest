# MapObject
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|Static|Boolean|False|Object does not move|
|Position|CustomLogicVector3Builtin|False|The position of the object|
|LocalPosition|CustomLogicVector3Builtin|False|The local position of the object|
|Rotation|CustomLogicVector3Builtin|False|The rotation of the object|
|LocalRotation|CustomLogicVector3Builtin|False|The local rotation of the object|
|QuaternionRotation|CustomLogicQuaternionBuiltin|False|The rotation of the object as a quaternion|
|QuaternionLocalRotation|CustomLogicQuaternionBuiltin|False|The local rotation of the object as a quaternion|
|Forward|CustomLogicVector3Builtin|False|The forward direction of the object|
|Up|CustomLogicVector3Builtin|False|The up direction of the object|
|Right|CustomLogicVector3Builtin|False|The right direction of the object|
|Scale|CustomLogicVector3Builtin|False|The scale of the object|
|Name|String|False|The name of the object|
|Parent|Object|False|The parent of the object|
|Active|Boolean|False|Whether the object is active|
|Transform|CustomLogicTransformBuiltin|False|The transform of the object|
|HasRenderer|Boolean|False|Whether the object has a renderer|
|Color|CustomLogicColorBuiltin|False|The color of the object|
|TextureTilingX|Single|False|The x tiling of the object's texture|
|TextureTilingY|Single|False|The y tiling of the object's texture|
|TextureOffsetX|Single|False|The x offset of the object's texture|
|TextureOffsetY|Single|False|The y offset of the object's texture|
|ID|Int32|False|The ID of the object|
|Tag|String|False|The tag of the object|
|Layer|Int32|False|The layer of the object|
## Methods
|Function|Returns|Description|
|---|---|---|
|AddComponent(name : String)|CustomLogicComponentInstance|Add a component to the object|
|RemoveComponent(name : String)|Void|Remove a component from the object|
|GetComponent(name : String)|CustomLogicComponentInstance|Get a component from the object|
|SetComponentEnabled(name : String, enabled : Boolean)|Void|Set whether a component is enabled|
|SetComponentsEnabled(enabled : Boolean)|Void|Set whether all components are enabled|
|AddSphereCollider(collideMode : String, collideWith : String, center : CustomLogicVector3Builtin, radius : Single)|Void|Add a sphere collider to the object|
|AddBoxCollider(collideMode : String, collideWith : String, center : CustomLogicVector3Builtin = , size : CustomLogicVector3Builtin = )|Void|Add a box collider to the object|
|AddSphereTarget(team : String, center : CustomLogicVector3Builtin, radius : Single)|CustomLogicMapTargetableBuiltin|Add a sphere target to the object|
|AddBoxTarget(team : String, center : CustomLogicVector3Builtin, size : CustomLogicVector3Builtin)|CustomLogicMapTargetableBuiltin|Add a box target to the object|
|GetChild(name : String)|CustomLogicMapObjectBuiltin|Get a child object by name|
|GetChildren()|CustomLogicListBuiltin|Get all child objects|
|GetTransform(name : String)|CustomLogicTransformBuiltin|Get a child transform by name|
|SetColorAll(color : CustomLogicColorBuiltin)|Void|Set the color of all renderers on the object|
|InBounds(position : CustomLogicVector3Builtin)|Boolean|Check if a position is within the object's bounds|
|GetBoundsAverageCenter()|CustomLogicVector3Builtin|Get the bounds average center|
|GetBoundsCenter()|CustomLogicVector3Builtin|Get the bounds center|
|GetBoundsSize()|CustomLogicVector3Builtin|Get the bounds size|
|GetBoundsMin()|CustomLogicVector3Builtin|Get the bounds min|
|GetBoundsMax()|CustomLogicVector3Builtin|Get the bounds max|
|GetBoundsExtents()|CustomLogicVector3Builtin|Get the bounds extents|
|GetCorners()|CustomLogicListBuiltin|Get the corners of the bounds|
|AddBuiltinComponent(parameter0 : Object = , parameter1 : Object = , parameter2 : Object = , parameter3 : Object = , parameter4 : Object = )|Void|[OBSELETE] Add builtin component|
|ReadBuiltinComponent(name : String, param : String)|Object|[OBSELETE] Read a builtin component|
|UpdateBuiltinComponent(parameter0 : Object = , parameter1 : Object = , parameter2 : Object = , parameter3 : Object = , parameter4 : Object = )|Void|[OBSELETE] Update a builtin component|

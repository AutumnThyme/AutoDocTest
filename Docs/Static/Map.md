# Map## Methods
|Function|Returns|Description|
|---|---|---|
|FindAllMapObjects()|CustomLogicListBuiltin|Find all map objects|
|FindMapObjectByName(objectName : String)|CustomLogicMapObjectBuiltin|Find a map object by name|
|FindMapObjectsByName(objectName : String)|CustomLogicListBuiltin|Find all map objects by name|
|FindMapObjectByComponent(className : String)|CustomLogicMapObjectBuiltin|Find all map objects by component|
|FindMapObjectsByComponent(className : String)|CustomLogicListBuiltin|Find all map objects by component|
|FindMapObjectByID(id : Int32)|CustomLogicMapObjectBuiltin|Find a map object by ID|
|FindMapObjectByTag(tag : String)|CustomLogicMapObjectBuiltin|Find a map object by tag|
|FindMapObjectsByTag(tag : String)|CustomLogicListBuiltin|Find all map objects by tag|
|CreateMapObjectRaw(prefab : String)|CustomLogicMapObjectBuiltin|Create a new map object|
|DestroyMapObject(mapObject : CustomLogicMapObjectBuiltin, includeChildren : Boolean)|Void|Destroy a map object|
|CopyMapObject(mapObject : CustomLogicMapObjectBuiltin, includeChildren : Boolean)|CustomLogicMapObjectBuiltin|Copy a map object|
|DestroyMapTargetable(targetable : CustomLogicMapTargetableBuiltin)|Void|Destroy a map targetable|
|UpdateNavMesh()|Void|Update the nav mesh|
|UpdateNavMeshAsync()|Void|Update the nav mesh asynchronously|

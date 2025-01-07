# Random## Methods
|Function|Returns|Description|
|---|---|---|
|RandomInt(min : Int32, max : Int32)|Int32|Generates a random integer between the specified range.|
|RandomFloat(min : Single, max : Single)|Single|Generates a random float between the specified range.|
|RandomBool()|Boolean|Returns random boolean.|
|RandomVector3(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|CustomLogicVector3Builtin|Generates a random Vector3 between the specified ranges.|
|RandomDirection(flat : Boolean = False)|CustomLogicVector3Builtin|Generates a random normalized direction vector. If flat is true, the y component will be zero.|
|RandomSign()|Int32|Generates a random sign, either 1 or -1.|
|PerlinNoise(x : Single, y : Single)|Single|Returns a point sampled from generated 2d perlin noise. (see Unity Mathf.PerlinNoise for more information)|

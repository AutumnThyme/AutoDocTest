# Color
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|R|Int32|False|Red component of the color|
|G|Int32|False|Green component of the color|
|B|Int32|False|Blue component of the color|
|A|Int32|False|Alpha component of the color|
## Methods
|Function|Returns|Description|
|---|---|---|
|ToHexString()|String|Converts the color to a hex string|
|Lerp(a : CustomLogicColorBuiltin, b : CustomLogicColorBuiltin, t : Single)|CustomLogicColorBuiltin|Linearly interpolates between colors a and b by t|
|Gradient(a : CustomLogicColorBuiltin, b : CustomLogicColorBuiltin, t : Single)|CustomLogicColorBuiltin|Creates a gradient color from two colors|

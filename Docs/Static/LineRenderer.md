# LineRenderer
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|StartWidth|Single|False|The width of the line at the start|
|EndWidth|Single|False|The width of the line at the end|
|LineColor|CustomLogicColorBuiltin|False|The color of the line|
|PositionCount|Int32|False|The number of points in the line|
|Enabled|Boolean|False|Is the line renderer enabled|
|Loop|Boolean|False|Is the line renderer a loop|
|NumCornerVertices|Int32|False|The number of corner vertices|
|NumCapVertices|Int32|False|The number of end cap vertices|
|Alignment|String|False|The alignment of the line renderer|
|TextureMode|String|False|The texture mode of the line renderer|
|UseWorldSpace|Boolean|False|Is the line renderer in world space|
|ShadowCastingMode|String|False|Does the line renderer cast shadows|
|ReceiveShadows|Boolean|False|Does the line renderer receive shadows|
|ColorGradient|CustomLogicListBuiltin|False|The gradient of the line renderer|
|AlphaGradient|CustomLogicListBuiltin|False|The alpha gradient of the line renderer|
|WidthCurve|CustomLogicListBuiltin|False|The width curve of the line renderer|
|WidthMultiplier|Single|False|The width multiplier of the line renderer|
|ColorGradientMode|String|False|The color gradient mode of the line renderer|
## Methods
|Function|Returns|Description|
|---|---|---|
|CreateLineRenderer()|CustomLogicLineRendererBuiltin|[Obselete] Create a new LineRenderer|
|GetPosition(index : Int32)|CustomLogicVector3Builtin|Get the position of a point in the line renderer|
|SetPosition(index : Int32, position : CustomLogicVector3Builtin)|Void|Set the position of a point in the line renderer|

# Vector2## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|X|Single|False||
|Y|Single|False||
|Normalized|CustomLogicVector2Builtin|False||
|Magnitude|Single|False||
|SqrMagnitude|Single|False||
|Zero|CustomLogicVector2Builtin|False||
|One|CustomLogicVector2Builtin|False||
|Up|CustomLogicVector2Builtin|False||
|Down|CustomLogicVector2Builtin|False||
|Left|CustomLogicVector2Builtin|False||
|Right|CustomLogicVector2Builtin|False||
|NegativeInfinity|CustomLogicVector2Builtin|False||
|PositiveInfinity|CustomLogicVector2Builtin|False||
## Methods
|Function|Returns|Description|
|---|---|---|
|Angle(from : CustomLogicVector2Builtin, to : CustomLogicVector2Builtin)|Single||
|ClampMagnitude(vector : CustomLogicVector2Builtin, maxLength : Single)|CustomLogicVector2Builtin||
|Distance(a : CustomLogicVector2Builtin, b : CustomLogicVector2Builtin)|Single||
|Dot(a : CustomLogicVector2Builtin, b : CustomLogicVector2Builtin)|Single||
|Lerp(a : CustomLogicVector2Builtin, b : CustomLogicVector2Builtin, t : Single)|CustomLogicVector2Builtin||
|LerpUnclamped(a : CustomLogicVector2Builtin, b : CustomLogicVector2Builtin, t : Single)|CustomLogicVector2Builtin||
|Max(a : CustomLogicVector2Builtin, b : CustomLogicVector2Builtin)|CustomLogicVector2Builtin||
|Min(a : CustomLogicVector2Builtin, b : CustomLogicVector2Builtin)|CustomLogicVector2Builtin||
|MoveTowards(current : CustomLogicVector2Builtin, target : CustomLogicVector2Builtin, maxDistanceDelta : Single)|CustomLogicVector2Builtin||
|Reflect(inDirection : CustomLogicVector2Builtin, inNormal : CustomLogicVector2Builtin)|CustomLogicVector2Builtin||
|SignedAngle(from : CustomLogicVector2Builtin, to : CustomLogicVector2Builtin)|Single||
|SmoothDamp(current : CustomLogicVector2Builtin, target : CustomLogicVector2Builtin, currentVelocity : CustomLogicVector2Builtin, smoothTime : Single, maxSpeed : Single)|CustomLogicVector2Builtin||
|Set(x : Single, y : Single)|Void||
|Normalize()|Void||
|__Copy__()|Object||
|__Add__(self : Object, other : Object)|Object||
|__Sub__(self : Object, other : Object)|Object||
|__Mul__(self : Object, other : Object)|Object||
|__Div__(self : Object, other : Object)|Object||
|__Eq__(self : Object, other : Object)|Boolean||
|__Hash__()|Int32||

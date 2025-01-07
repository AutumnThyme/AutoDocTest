# Vector3## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|X|Single|False||
|Y|Single|False||
|Z|Single|False||
|Normalized|CustomLogicVector3Builtin|False||
|Magnitude|Single|False||
|SqrMagnitude|Single|False||
|Zero|CustomLogicVector3Builtin|False||
|One|CustomLogicVector3Builtin|False||
|Up|CustomLogicVector3Builtin|False||
|Down|CustomLogicVector3Builtin|False||
|Left|CustomLogicVector3Builtin|False||
|Right|CustomLogicVector3Builtin|False||
|Forward|CustomLogicVector3Builtin|False||
|Back|CustomLogicVector3Builtin|False||
|NegativeInfinity|CustomLogicVector3Builtin|False||
|PositiveInfinity|CustomLogicVector3Builtin|False||
## Methods
|Function|Returns|Description|
|---|---|---|
|Angle(from : CustomLogicVector3Builtin, to : CustomLogicVector3Builtin)|Single||
|ClampMagnitude(vector : CustomLogicVector3Builtin, maxLength : Single)|CustomLogicVector3Builtin||
|Cross(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|Distance(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|Single||
|Dot(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|Single||
|Lerp(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin, t : Single)|CustomLogicVector3Builtin||
|LerpUnclamped(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin, t : Single)|CustomLogicVector3Builtin||
|Max(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|Min(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|MoveTowards(current : CustomLogicVector3Builtin, target : CustomLogicVector3Builtin, maxDistanceDelta : Single)|CustomLogicVector3Builtin||
|Normalize(value : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|OrthoNormalize(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|Void||
|Project(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|ProjectOnPlane(vector : CustomLogicVector3Builtin, plane : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|Reflect(inDirection : CustomLogicVector3Builtin, inNormal : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|RotateTowards(current : CustomLogicVector3Builtin, target : CustomLogicVector3Builtin, maxRadiansDelta : Single, maxMagnitudeDelta : Single)|CustomLogicVector3Builtin||
|SignedAngle(from : CustomLogicVector3Builtin, to : CustomLogicVector3Builtin, axis : CustomLogicVector3Builtin)|Single||
|Slerp(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin, t : Single)|CustomLogicVector3Builtin||
|SlerpUnclamped(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin, t : Single)|CustomLogicVector3Builtin||
|SmoothDamp(current : CustomLogicVector3Builtin, target : CustomLogicVector3Builtin, currentVelocity : CustomLogicVector3Builtin, smoothTime : Single, maxSpeed : Single)|CustomLogicVector3Builtin||
|Set(x : Single, y : Single, z : Single)|Void||
|Scale(scale : Object)|CustomLogicVector3Builtin||
|Multiply(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|Divide(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|GetRotationDirection(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|CustomLogicVector3Builtin||
|__Copy__()|Object||
|__Add__(self : Object, other : Object)|Object||
|__Sub__(self : Object, other : Object)|Object||
|__Mul__(self : Object, other : Object)|Object||
|__Div__(self : Object, other : Object)|Object||
|__Eq__(self : Object, other : Object)|Boolean||
|__Hash__()|Int32||

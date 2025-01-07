# Quaternion
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|X|Single|False||
|Y|Single|False||
|Z|Single|False||
|W|Single|False||
|EulerAngles|CustomLogicVector3Builtin|False||
|Identity|CustomLogicQuaternionBuiltin|False||
## Methods
|Function|Returns|Description|
|---|---|---|
|Lerp(a : CustomLogicQuaternionBuiltin, b : CustomLogicQuaternionBuiltin, t : Single)|CustomLogicQuaternionBuiltin||
|LerpUnclamped(a : CustomLogicQuaternionBuiltin, b : CustomLogicQuaternionBuiltin, t : Single)|CustomLogicQuaternionBuiltin||
|Slerp(a : CustomLogicQuaternionBuiltin, b : CustomLogicQuaternionBuiltin, t : Single)|CustomLogicQuaternionBuiltin||
|SlerpUnclamped(a : CustomLogicQuaternionBuiltin, b : CustomLogicQuaternionBuiltin, t : Single)|CustomLogicQuaternionBuiltin||
|FromEuler(euler : CustomLogicVector3Builtin)|CustomLogicQuaternionBuiltin||
|LookRotation(forward : CustomLogicVector3Builtin, upwards : CustomLogicVector3Builtin)|CustomLogicQuaternionBuiltin||
|FromToRotation(a : CustomLogicVector3Builtin, b : CustomLogicVector3Builtin)|CustomLogicQuaternionBuiltin||
|Inverse(q : CustomLogicQuaternionBuiltin)|CustomLogicQuaternionBuiltin||
|RotateTowards(from : CustomLogicQuaternionBuiltin, to : CustomLogicQuaternionBuiltin, maxDegreesDelta : Single)|CustomLogicQuaternionBuiltin||
|__Copy__()|Object||
|__Add__(self : Object, other : Object)|Object||
|__Sub__(self : Object, other : Object)|Object||
|__Mul__(self : Object, other : Object)|Object||
|__Div__(self : Object, other : Object)|Object||
|__Eq__(self : Object, other : Object)|Boolean||
|__Hash__()|Int32||

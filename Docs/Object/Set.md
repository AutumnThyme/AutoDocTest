# Set## Initialization
```csharp
new Set()
new Set((CustomLogicListBuiltin))
```
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|Count|Int32|True|The number of elements in the set|
## Methods
|Function|Returns|Description|
|---|---|---|
|Clear()|Void|Clear all set elements|
|Contains(value : Object)|Boolean|Check if the set contains the specified element|
|Add(value : Object)|Void|Add an element to the set|
|Remove(value : Object)|Void|Remove the element from the set|
|Union(set : CustomLogicSetBuiltin)|Void|Union with another set|
|Intersect(set : CustomLogicSetBuiltin)|Void|Intersect with another set|
|Difference(set : CustomLogicSetBuiltin)|Void|Difference with another set|
|IsSubsetOf(set : CustomLogicSetBuiltin)|Boolean|Check if the set is a subset of another set|
|IsSupersetOf(set : CustomLogicSetBuiltin)|Boolean|Check if the set is a superset of another set|
|IsProperSubsetOf(set : CustomLogicSetBuiltin)|Boolean|Check if the set is a proper subset of another set|
|IsProperSupersetOf(set : CustomLogicSetBuiltin)|Boolean|Check if the set is a proper superset of another set|
|Overlaps(set : CustomLogicSetBuiltin)|Boolean|Check if the set overlaps with another set|
|SetEquals(set : CustomLogicSetBuiltin)|Boolean|Check if the set has the same elements as another set|
|ToList()|CustomLogicListBuiltin|Convert the set to a list|

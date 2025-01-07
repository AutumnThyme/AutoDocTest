# List## Initialization
```csharp
new List()
new List((CustomLogicSetBuiltin))
```
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|Count|Int32|True|The number of elements in the list|
## Methods
|Function|Returns|Description|
|---|---|---|
|Clear()|Void|Clear all list elements|
|Get(index : Int32)|Object|Get the element at the specified index|
|Set(index : Int32, value : Object)|Void|Set the element at the specified index|
|Add(value : Object)|Void|Add an element to the end of the list|
|InsertAt(index : Int32, value : Object)|Void|Insert an element at the specified index|
|RemoveAt(index : Int32)|Void|Remove the element at the specified index|
|Remove(value : Object)|Void|Remove the first occurrence of the specified element|
|Contains(value : Object)|Boolean|Check if the list contains the specified element|
|Sort()|Void|Sort the list|
|SortCustom(method : UserMethod)|Void|Sort the list using a custom method, expects a method with the signature int method(a,b)|
|Filter(method : UserMethod)|CustomLogicListBuiltin|Filter the list using a custom method, expects a method with the signature bool method(element)|
|Map(method : UserMethod)|CustomLogicListBuiltin|Map the list using a custom method, expects a method with the signature object method(element)|
|Reduce(method : UserMethod, initialValue : Object)|Object|Reduce the list using a custom method, expects a method with the signature object method(acc, element)|
|Randomize()|Void|Randomize the list|
|ToSet()|CustomLogicSetBuiltin|Convert the list to a set|

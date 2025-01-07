# String
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|Newline|String|False|Returns the newline character.|
## Methods
|Function|Returns|Description|
|---|---|---|
|FormatFloat(val : Single, decimals : Int32)|String|Formats a float to a string with the specified number of decimal places.|
|FormatFromList(str : String, list : CustomLogicListBuiltin)|String|Equivalent to C# string.format(string, List<string>).|
|Split(toSplit : String, splitter : Object, removeEmptyEntries : Boolean = False)|CustomLogicListBuiltin|Split the string into a list. Can pass in either a string to split on or a list of strings to split on, the last optional param can remove all empty entries.|
|Join(list : CustomLogicListBuiltin, separator : String)|String|Joins a list of strings into a single string with the specified separator.|
|Substring(str : String, startIndex : Int32)|String|Returns a substring starting from the specified index.|
|SubstringWithLength(str : String, startIndex : Int32, length : Int32)|String|Returns a substring of the specified length starting from the specified start index.|
|Length(str : String)|Int32|Length of the string.|
|Replace(str : String, replace : String, with : String)|String|Replaces all occurrences of a substring with another substring.|
|Contains(str : String, match : String)|Boolean|Checks if the string contains the specified substring.|
|StartsWith(str : String, match : String)|Boolean|Checks if the string starts with the specified substring.|
|EndsWith(str : String, match : String)|Boolean|Checks if the string ends with the specified substring.|
|Trim(str : String)|String|Trims whitespace from the start and end of the string.|
|Insert(str : String, insert : String, index : Int32)|String|Inserts a substring at the specified index.|
|Capitalize(str : String)|String|Capitalizes the first letter of the string.|
|ToUpper(str : String)|String|Converts the string to uppercase.|
|ToLower(str : String)|String|Converts the string to lowercase.|
|IndexOf(str : String, substring : String)|Int32|Returns the index of the given string.|

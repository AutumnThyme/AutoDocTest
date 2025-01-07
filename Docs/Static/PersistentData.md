# PersistentData## Methods
|Function|Returns|Description|
|---|---|---|
|SetProperty(property : String, value : Object)|Void|Sets the property with given name to the object value. Valid value types are float, string, bool, and int.|
|GetProperty(property : String, defaultValue : Object)|Object|Gets the property with given name. If property does not exist, returns defaultValue.|
|LoadFromFile(fileName : String, encrypted : Boolean)|Void|Loads persistent data from given file name. If encrypted is true, will treat the file as having been saved as encrypted.|
|SaveToFile(fileName : String, encrypted : Boolean)|Void|Saves current persistent data to given file name. If encrypted is true, will also encrypt the file instead of using plaintext.|
|Clear()|Void|Clears current persistent data.|
|IsValidFileName(fileName : String)|Boolean|Determines whether or not the given fileName will be allowed for use when saving/loading a file.|
|FileExists(fileName : String)|Boolean|Determines whether the file given already exists. Throws an error if given an invalid file name.|

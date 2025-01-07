# Player## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|Character|Object|False|Player's current character, if alive.|
|Connected|Boolean|False|Player is still connected to the room.|
|ID|Int32|False|Player unique ID.|
|Name|String|False|Player name.|
|Guild|String|False|Player guild.|
|Team|String|False||
|Status|String|False|Player's spawn status ("Alive", "Dead", "Spectating").|
|CharacterType|String|False|Player's chosen character ("Human", "Titan", "Shifter")|
|Loadout|String|False|Player's chosen loadout ("Blades", "AHSS", "APG", "Thunderspears").|
|Kills|Int32|False|Player's kills.|
|Deaths|Int32|False|Player's deaths.|
|HighestDamage|Int32|False|Player's highest damage.|
|TotalDamage|Int32|False|Player's total damage.|
|Ping|Int32|False|The player's connection ping.|
|SpectateID|Int32|False|The player's spectating ID. If not spectating anyone, returns -1.|
|SpawnPoint|CustomLogicVector3Builtin|False|Player's respawn point. Is initially null and can be set back to null, at which point map spawn points are used.|
## Methods
|Function|Returns|Description|
|---|---|---|
|GetCustomProperty(property : String)|Object|Get a custom property at given key. Must be a primitive type. This is synced to all clients.|
|SetCustomProperty(property : String, value : Object)|Void|Sets a custom property at given key. Must be a primitive type. This is synced to all clients.|
|ClearKDR()|Void|Clears kills, deaths, highestdamage, and totaldamage properties.|

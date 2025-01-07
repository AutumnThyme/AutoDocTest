# Network
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|IsMasterClient|Boolean|False|Is the player the master client|
|Players|CustomLogicListBuiltin|False|The list of players in the room|
|MasterClient|CustomLogicPlayerBuiltin|False|The master client|
|MyPlayer|CustomLogicPlayerBuiltin|False|The local player|
|NetworkTime|Double|False|The network time|
|Ping|Int32|False|The local player's ping|
## Methods
|Function|Returns|Description|
|---|---|---|
|SendMessage(player : CustomLogicPlayerBuiltin, message : String)|Void|Send a message to a player|
|SendMessageAll(message : String)|Void|Send a message to all players|
|SendMessageOthers(message : String)|Void|Send a message to all players except the sender|
|GetTimestampDifference(timestamp1 : Double, timestamp2 : Double)|Double|Get the difference between two photon timestamps|
|KickPlayer(target : Object, reason : String = .)|Void|Kick the given player by id or player reference.|

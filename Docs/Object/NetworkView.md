# NetworkView## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|Owner|CustomLogicPlayerBuiltin|False|The network view's owner.|
## Methods
|Function|Returns|Description|
|---|---|---|
|Transfer(player : CustomLogicPlayerBuiltin)|Void|Owner only. Transfer ownership of this NetworkView to another player.|
|SendMessage(target : CustomLogicPlayerBuiltin, msg : String)|Void|Send a message to a target player. This will be received in any of the MapObject attached components through the OnNetworkMessage callback.|
|SendMessageAll(msg : String)|Void|Send a message to all players including myself.|
|SendMessageOthers(msg : String)|Void|Send a message to players excluding myself.|
|SendStream(obj : Object)|Void||
|ReceiveStream()|Object||

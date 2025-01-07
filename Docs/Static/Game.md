# Game
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|IsEnding|Boolean|False|Is the game ending?|
|EndTimeLeft|Single|False|Time left until the game ends|
|Titans|CustomLogicListBuiltin|False|List of all titans|
|AITitans|CustomLogicListBuiltin|False|List of all AI titans|
|PlayerTitans|CustomLogicListBuiltin|False|List of all player titans|
|Shifters|CustomLogicListBuiltin|False|List of all shifters|
|AIShifters|CustomLogicListBuiltin|False|List of all AI shifters|
|PlayerShifters|CustomLogicListBuiltin|False|List of all player shifters|
|Humans|CustomLogicListBuiltin|False|List of all humans|
|AIHumans|CustomLogicListBuiltin|False|List of all AI humans|
|PlayerHumans|CustomLogicListBuiltin|False|List of all player humans|
|Loadouts|CustomLogicListBuiltin|False|List of all loadouts|
|DefaultShowKillScore|Boolean|False|Is the kill score shown by default?|
|DefaultHideKillScore|Boolean|False|Is the kill feed shown by default?|
|DefaultAddKillScore|Boolean|False|Is the kill score added by default?|
|ShowScoreboardLoadout|Boolean|False|Is the loadout shown in the scoreboard?|
|ShowScoreboardStatus|Boolean|False|Is the status shown in the scoreboard?|
|ForcedCharacterType|String|False|Forced character type|
|ForcedLoadout|String|False|Forced loadout|
## Methods
|Function|Returns|Description|
|---|---|---|
|Debug(message : Object)|Void|Print a debug statement to the console|
|Print(message : Object)|Void|Print a message to the chat|
|PrintAll(message : Object)|Void|Print a message to all players|
|GetGeneralSetting(settingName : String)|Object|Get a general setting|
|GetTitanSetting(settingName : String)|Object|Get a titan setting|
|GetMiscSetting(settingName : String)|Object|Get a misc setting|
|End(delay : Single)|Void|End the game|
|FindCharacterByViewID(viewID : Int32)|CustomLogicCharacterBuiltin|Find a character by view ID|
|SpawnTitan(type : String)|CustomLogicTitanBuiltin|Spawn a titan|
|SpawnTitanAt(type : String, position : CustomLogicVector3Builtin, rotationY : Single = 0)|CustomLogicTitanBuiltin|Spawn a titan at a position|
|SpawnTitans(type : String, count : Int32)|CustomLogicListBuiltin|Spawn titans|
|SpawnTitansAsync(type : String, count : Int32)|Void|Spawn titans asynchronously|
|SpawnTitansAt(type : String, count : Int32, position : CustomLogicVector3Builtin, rotationY : Single = 0)|CustomLogicListBuiltin|Spawn titans at a position|
|SpawnTitansAtAsync(type : String, count : Int32, position : CustomLogicVector3Builtin, rotationY : Single = 0)|Void|Spawn titans at a position asynchronously|
|SpawnShifter(type : String)|CustomLogicShifterBuiltin|Spawn a shifter|
|SpawnShifterAt(type : String, position : CustomLogicVector3Builtin, rotationY : Single = 0)|CustomLogicShifterBuiltin|Spawn a shifter at a position|
|SpawnProjectile(parameters : Object[])|Void|Spawn a projectile|
|SpawnProjectileWithOwner(parameters : Object[])|Void|Spawn a projectile with an owner|
|SpawnEffect(parameters : Object[])|Void|Spawn an effect|
|SpawnPlayer(player : CustomLogicPlayerBuiltin, force : Boolean)|Void|Spawn a player|
|SpawnPlayerAll(force : Boolean)|Void|Spawn a player for all players|
|SpawnPlayerAt(player : CustomLogicPlayerBuiltin, force : Boolean, position : CustomLogicVector3Builtin, rotationY : Single = 0)|Void|Spawn a player at a position|
|SpawnPlayerAtAll(force : Boolean, position : CustomLogicVector3Builtin, rotationY : Single = 0)|Void|Spawn a player at a position for all players|
|SetPlaylist(playlist : String)|Void|Set the music playlist|
|SetSong(song : String)|Void|Set the music song|
|DrawRay(start : CustomLogicVector3Builtin, dir : CustomLogicVector3Builtin, color : Color, duration : Single)|Void|Draw a ray|
|ShowKillScore(damage : Int32)|Void|Show the kill score|
|ShowKillFeed(killer : String, victim : String, score : Int32, weapon : String)|Void|Show the kill feed|
|ShowKillFeedAll(killer : String, victim : String, score : Int32, weapon : String)|Void|Show the kill feed for all players|

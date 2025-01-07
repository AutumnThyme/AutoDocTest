# Shifter
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|Size|Single|False|Shifter's size.|
|RunSpeedBase|Single|False|Shifter's base run speed. Final run speed is RunSpeedBase + Size * RunSpeedPerLevel.|
|WalkSpeedBase|Single|False|Shifter's base walk speed. Final walk speed is WalkSpeedBase + Size * WalkSpeedPerLevel.|
|WalkSpeedPerLevel|Single|False|Shifter's walk speed added per level.|
|RunSpeedPerLevel|Single|False|Shifter's run speed added per level.|
|TurnSpeed|Single|False|Shifter's turn speed when running turn animation.|
|RotateSpeed|Single|False|Shifter's rotate speed when rotating body.|
|JumpForce|Single|False|Shifter's jump force when jumping.|
|ActionPause|Single|False|Shifter's pause delay after performing an action.|
|AttackPause|Single|False|Shifter's pause delay after performing an attack.|
|TurnPause|Single|False|Shifter's pause delay after performing a turn.|
|DetectRange|Single|False|(AI) shifter's detect range.|
|FocusRange|Single|False|(AI) shifter's focus range.|
|FocusTime|Single|False|(AI) shifter's focus time before switching targets.|
|FarAttackCooldown|Single|False|(AI) Shifter's cooldown after performing a ranged attack.|
|AttackWait|Single|False|(AI) Shifter's wait time between being in range to attack and performing the attack.|
|AttackSpeedMultiplier|Single|False|Shifter's attack animation speed.|
|UsePathfinding|Boolean|False|(AI) Shifter uses pathfinding.|
|NapePosition|CustomLogicVector3Builtin|False|The shifter's nape position.|
|DeathAnimLength|Single|False|The length of the death animation.|
|Player|CustomLogicPlayerBuiltin|False|Player who owns this character.|
|IsAI|Boolean|False|Is this character AI?|
|ViewID|Int32|False|Network view ID of the character.|
|IsMine|Boolean|False|Is this character mine?|
|IsMainCharacter|Boolean|False||
|Transform|CustomLogicTransformBuiltin|False|Unity transform of the character.|
|Position|CustomLogicVector3Builtin|False|Position of the character.|
|Rotation|CustomLogicVector3Builtin|False|Rotation of the character.|
|QuaternionRotation|CustomLogicQuaternionBuiltin|False|Quaternion rotation of the character.|
|Velocity|CustomLogicVector3Builtin|False|Velocity of the character.|
|Forward|CustomLogicVector3Builtin|False|Forward direction of the character.|
|Right|CustomLogicVector3Builtin|False|Right direction of the character.|
|Up|CustomLogicVector3Builtin|False|Up direction of the character.|
|HasTargetDirection|Boolean|False|If the character has a target direction it is turning towards.|
|TargetDirection|CustomLogicVector3Builtin|False|The character's target direction.|
|Team|String|False|Team character belongs to.|
|Name|String|False|The display name of the character.|
|Guild|String|False|The guild name of the character.|
|Health|Single|False|Character's current health.|
|MaxHealth|Single|False|Character's maximum health.|
|CustomDamageEnabled|Boolean|False|Is custom damage dealing enabled.|
|CustomDamage|Int32|False|Amount of custom damage to deal per attack.|
|CurrentAnimation|String|False|Character's current playing animation.|
|Grounded|Boolean|False|Character's grounded status.|
## Methods
|Function|Returns|Description|
|---|---|---|
|MoveTo(position : CustomLogicVector3Builtin, range : Single, ignoreEnemies : Boolean)|Void|Causes the (AI) shifter to move towards a position. If ignoreEnemies is true, will not engage enemies along the way.|
|Target(enemyObj : Object, focus : Single)|Void|Causes the (AI) shifter to target an enemy character or MapTargetable for focusTime seconds. If focusTime is 0 it will use the default focus time.|
|Idle(time : Single)|Void|Causes the (AI) shifter to idle for time seconds before beginning to wander. During idle the titan will not react or move at all.|
|Wander()|Void|Causes the (AI) shifter to cancel any move commands and begin wandering randomly.|
|Blind()|Void|Causes the shifter to enter the blind state.|
|Cripple(time : Single)|Void|Causes the shifter to enter the cripple state.|
|GetKilled(killer : String)|Void|Kills the character. Callable by non-owners.|
|GetDamaged(killer : String, damage : Int32)|Void|Damages the character and kills it if its health reaches 0. Callable by non-owners.|
|Emote(emote : String)|Void|Causes the character to emote. The list of available emotes is the same as those shown in the in-game emote menu.|
|PlayAnimation(animation : String, fade : Single = 0.1)|Void|Causes the character to play an animation.  If the fade parameter is provided, will crossfade the animation by this timestep. Available animations can be found here: Human, Titan, Annie, Eren. Use the right-hand string value for the animation.|
|GetAnimationLength(animation : String)|Single|Gets the length of animation.|
|PlaySound(sound : String)|Void|Plays a sound if present in the character. Available sound names can be found here: Humans, Shifters, Titans. Note that shifters also have all titan sounds.|
|StopSound(sound : String)|Void|Stops the sound.|
|LookAt(position : CustomLogicVector3Builtin)|Void|Rotates the character such that it is looking towards a world position.|
|AddForce(force : CustomLogicVector3Builtin, mode : String = Acceleration)|Void|Adds a force to the character with given force vector and optional mode. Valid modes are Force, Acceleration, Impulse, VelocityChange with default being Acceleration.|
|Reveal(delay : Single)|Void|Reveaal the titan for a set number of seconds.|
|AddOutline(color : CustomLogicColorBuiltin = , mode : String = OutlineAll)|Void|Adds an outline effect with the given color and mode. Valid modes are: OutlineAll, OutlineVisible, OutlineHidden, OutlineAndSilhouette, SilhouetteOnly, OutlineAndLightenColor|
|RemoveOutline()|Void|Removes the outline effect from the character.|

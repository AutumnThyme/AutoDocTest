# Human## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|Weapon|String|False|The weapon the human is using|
|CurrentSpecial|String|False|The current special the human is using|
|SpecialCooldown|Single|False|The cooldown of the special|
|ShifterLiveTime|Single|False|The live time of the shifter special|
|SpecialCooldownRatio|Single|False|The ratio of the special cooldown|
|CurrentGas|Single|False|The current gas of the human|
|MaxGas|Single|False|The max gas of the human|
|Acceleration|Int32|False|The acceleration of the human|
|Speed|Int32|False|The speed of the human|
|HorseSpeed|Single|False|The speed of the horse|
|CurrentBladeDurability|Single|False|The current blade durability|
|MaxBladeDurability|Single|False|The max blade durability|
|CurrentBlade|Int32|False|The current blade|
|MaxBlade|Int32|False|The max number of blades held|
|CurrentAmmoRound|Int32|False|The current ammo round|
|MaxAmmoRound|Int32|False|The max ammo round|
|CurrentAmmoLeft|Int32|False|The current ammo left|
|MaxAmmoTotal|Int32|False|The max total ammo|
|LeftHookEnabled|Boolean|False|Whether the left hook is enabled|
|RightHookEnabled|Boolean|False|Whether the right hook is enabled|
|IsMounted|Boolean|False|Whether the human is mounted|
|MountedMapObject|CustomLogicMapObjectBuiltin|False|The map object the human is mounted on|
|MountedTransform|CustomLogicTransformBuiltin|False|The transform the human is mounted on|
|AutoRefillGas|Boolean|False|Whether the human auto refills gas|
|State|String|False|The state of the human|
|CanDodge|Boolean|False|Whether the human can dodge|
|IsInvincible|Boolean|False|Whether the human is invincible|
|InvincibleTimeLeft|Single|False|The time left for invincibility|
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
|Refill()|Boolean|Refills the gas of the human|
|RefillImmediate()|Void|Refills the gas of the human immediately|
|ClearHooks()|Void|Clears all hooks|
|ClearLeftHook()|Void|Clears the left hook|
|ClearRightHook()|Void|Clears the right hook|
|MountMapObject(mapObject : CustomLogicMapObjectBuiltin, positionOffset : CustomLogicVector3Builtin, rotationOffset : CustomLogicVector3Builtin)|Void|Mounts the human on a map object|
|MountTransform(transform : CustomLogicTransformBuiltin, positionOffset : CustomLogicVector3Builtin, rotationOffset : CustomLogicVector3Builtin)|Void|Mounts the human on a transform|
|Unmount()|Void|Unmounts the human|
|SetSpecial(special : String)|Void|Sets the special of the human|
|ActivateSpecial()|Void|Activates the special of the human|
|SetWeapon(weapon : String)|Void|Sets the weapon of the human|
|DisablePerks()|Void|Disables all perks of the human|
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

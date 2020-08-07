# GUC-Configs
If you want to add any make a pull request


# ENTWATCH TEMPLATE


```
"entities"
{
	"0"
	{
		"name"				""			//String, FullName of Item (Chat)
		"shortname"			""			//String, ShortName of Item (Hud)
		"color"				""			//String, One of the colors. (Chat, Glow)
		"buttonclass"			""			//String, Button Class, May matter "game_ui" for Right Click activation method
		"filtername"			""			//String, Filter for Activator
		"blockpickup"			"false"			//Bool, should always be false
		"allowtransfer"			"false"			//Bool, True for human, false for ZM item
		"forcedrop"			"false"			//Bool, Upon death or disconnection of the player, the item will be thrown out True for human, false for ZM item
		"chat"				"false"			//Bool, Display chat items
		"chat_uses"			"false"			//Bool, Display chat someone is using an item(if disabled chat)
		"hud"				"false"			//Bool, Display Hud items
		"hammerid"			"0"			//Integer, Special weapon HammerID
		"energyid"			"0"			//Integer, NEW! Math counter HammerID (For modes 6 & 7)
		"mode"				"0"			//Integer, Mode for Item. 1 = Spam protection only, 2 = Cooldowns, 3 = Limited uses, 4 = Limited uses with cooldowns, 5 = Cooldowns after multiple uses, 6 = Energy - stops when minimum reached, 7 = Energy - stops when maximum hit
		"maxuses"			"0"			//Integer, Maximum uses for modes 3,4,5
		"cooldown"			"0"			//Integer, Cooldown of item for modes 2,4,5
		"buttonid"			"0"			//Integer, Allows you to set the main button for which the cooldown will be considered. Use HammerID of button
		"trigger"			"0"			//Integer, Sets a trigger that a restrict player cannot activate e.g. knife item strip trigger
	}
} 
```


# GUC-Configs
If you want to add any make a pull request


## ENTWATCH TEMPLATE


```
"entities"
{
	"0"
	{
		"name"				""		//String, Name shown when picked up/dropped
		"shortname"			""		//String, Name that shows on HUD
		"color"				""		//String, Color shown in chat/glow
		"buttonclass"			""		//String, classname of the button, game_ui if right-click item
		"filtername"			""		//String, Filter for Activator
		"blockpickup"			"false"		//Bool, should always be false
		"allowtransfer"			"false"		//Bool, True for human, false for ZM item
		"forcedrop"			"false"		//Bool, True if pistol item, false if knife item
		"chat"				"false"		//Bool, Show when item picked up/used/dropped in chat
		"chat_uses"			"false"		//Bool, Show when item used in chat (only if "chat" is false)
		"hud"				"false"		//Bool, Should item show on HUD
		"hammerid"			"0"		//Integer, HammerID of item weapon
		"energyid"			"0"		//Integer, Math counter HammerID (For modes 6 & 7)
		"mode"				"0"		//Integer, Mode for Item. 1 = Spam protection only, 2 = Cooldowns, 3 = Limited uses, 4 = Limited uses with cooldowns, 5 = Cooldowns after multiple uses, 6 = Energy - stops when minimum reached, 7 = Energy - stops when maximum hit
		"maxuses"			"0"		//Integer, Maximum uses for modes 3,4,5
		"cooldown"			"0"		//Integer, Cooldown of item for modes 2,4,5
		"buttonid"			"0"		//Integer, If an item has more than 1 button, set the hammerID of the button to be considered
		"trigger"			"0"		//Integer, HammerID of a trigger that a restricted player cannot activate e.g. knife item strip trigger
	}
} 
```
## Available Colors

```
{default}
{darkred}
{purple}
{green}
{lightgreen}
{lime}
{red}
{grey}
{olive}
{lightblue}
{blue}
{pink}
{darkorange}
{orange}
{white}
{yellow}
{magenta}
{silver}
{bluegrey}
{lightred}
{cyan}
{gray}
```

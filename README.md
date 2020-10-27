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
		"buttonclass"			""		//String, classname of the button, game_ui if right-click item, most likely func_button otherwise
		"filtername"			""		//String, Filter for Activator
		"blockpickup"			"false"		//Bool, should always be false
		"allowtransfer"			"false"		//Bool, True if pistol item, false if knife item
		"forcedrop"			"false"		//Bool, True if pistol item, false if knife item
		"chat"				"false"		//Bool, Show when item picked up/used/dropped in chat
		"chat_uses"			"false"		//Bool, Show when item used in chat (only if "chat" is false), doesn't say when picked/dropped
		"hud"				"false"		//Bool, Should item show on HUD
		"hammerid"			"0"		//Integer, HammerID of the item's weapon entity
		"energyid"			"0"		//Integer, Math counter HammerID (For modes 6 & 7)
		"mode"				"0"		//Integer, Mode for Item. 1 = Spam protection only, 2 = Cooldowns, 3 = Limited uses, 4 = Limited uses with cooldowns, 5 = Cooldowns after multiple uses, 6 = Energy - stops when minimum hit, 7 = Energy - stops when maximum hit
		"maxuses"			"0"		//Integer, Maximum uses for modes 3,4,5
		"cooldown"			"0"		//Integer, Cooldown of item for modes 2,4,5
		"buttonid"			"0"		//Integer, If an item has more than 1 button, set the hammerID of the button to be considered
		"trigger"			"0"		//Integer, HammerID of a trigger that a restricted player cannot activate e.g. knife item strip trigger
		"physbox"			"false"		//Bool, If the item has a physbox as part of it, setting to true will allow grenades to pass through
	}
} 
```
## Available Colors

```
{default}			{darkred}
{purple}			{green}
{lightgreen}			{lime}
{red}				{grey}
{olive}				{lightblue}
{blue}				{pink}
{darkorange}			{orange}
{white}				{yellow}
{magenta}			{silver}
{bluegrey}			{lightred}
{cyan}				{gray}
```


## BossHud Template

```
"bosses"
{
	"0"
	{
		"name"			""	// String, name that shows up on the HUD
		"method"		""	// breakable, counter, hp, hpbar
		"trigger"		""	// example: "trigger_boss:OnStartTouch:5" or "#hammerid:OnStartTouch:5"
		
		
		
		//Optional keyvalues
		"hitcounter"		""	// 1/0, true by default, only add if it needs to be false
		"physbox"		""	// Name of physbox/breakable to override hit counter if hits are not counted correctly
		"hidehud"		""	// 1/0, true by default, only add if the hud is not needed e.g. surf_dark_fantasy
		"breakable"		""	// Either breakable or counter is needed for it to work
		"counter"		""	// If method is counter, name/hammerid of the hp counter
		"showtrigger"		""	// the trigger to start showing the bhud
		"iterator"		""
		"backup"		""
		"killtrigger"		""	// Trigger to stop showing the HUD
		"multitrigger"		""
		"namefixup"		""
		"timeout"		""	// time bhud will stay visible
		"altHP"			""	// Instead of HP it will say this
	}
}
```
		
		

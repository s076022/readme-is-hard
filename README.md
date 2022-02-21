# RoseGoldAddons Feature List:
### Keybinds:
<details><summary>Auto Arrow Align</summary>
	
- Click keybind to instantly solve Floor 7's Arrow Align terminal
		
</details>
<details><summary>Blood Triggerbot</summary>
	
- Toggle to shoot blood room enemies that are looked at
		
</details>
<details><summary>Brewing Macro</summary>
	
- Toggle to start automatically brewing potions
- Supports Speed and  Weakness potions
- Change modes and other options in the RoseGoldAddons config menu under "Alchemy"
	
</details>
<details><summary>Crop Nuker</summary>
	
- Toggle to start breaking crops in range of the player
- Change configuration in the RoseGoldAddons config menu under "Farming"
	
</details>
<details><summary>Custom Item Macro</summary>
	
- Toggle to start all Custom Item Macros
- See [Explanation of Custom Item Macros](#explanation-of-custom-item-macros)
- Saves between sessions
</details>
<details><summary>Enderman Macro</summary>
	
- Toggle to start Enderman Macro
- Uses Precursor Eye to shoot Endermen around the player
- Change configuration in the RoseGoldAddons config menu under "Macros"
</details>
<details><summary>Foraging Island Macro</summary>
	
- Toggle to start Foraging Island Macro
- Change configuration in the RoseGoldAddons config menu under "Foraging"
- See [Explanation of Foraging Island Macro](#explanation-of-foraging-island-macro)
</details>
<details><summary>Foraging Nuker</summary>
	
- Toggle to start foraging trees in range of the player
</details>
<details><summary>Gemstone Nuker</summary>
	
- Toggle to start mining gemstones in range of the player
- Uses Mining Speed Boost
</details>
<details><summary>Ghost Macro</summary>
	
- Toggle to start looking at closest ghost
- Recommended to use with other features such as custom item macros
</details>
<details><summary>Hardstone Nuker</summary>
	
- Toggle to start Hardstone Nuker
- Includes powder chest solver
- Change configuration in the RoseGoldAddons config menu under "Mining"
</details>
<details><summary>Hardstone Nuker</summary>
	
- Toggle to start Hardstone Nuker
- Includes powder chest solver
- Change configuration in the RoseGoldAddons config menu under "Mining"
</details>
<details><summary>Mithril Macro</summary>
	
- Toggle to start a "legit" version of Mithril Nuker
</details>
<details><summary>Mithril Nuker</summary>

- Toggle to start a Mithril Nuker
- Automatically mines mithril around the player
- Change configuration in the RoseGoldAddons config menu under "Mining"
- No failsafes
</details>
<details><summary>Mithril Nuker</summary>
	
- Toggle to start a Mithril Nuker
- Automatically mines mithril around the player
- Change configuration in the RoseGoldAddons config menu under "Mining"
- No failsafes
</details>
<details><summary>Necron Aimbot</summary>
	
- Toggle to lock onto necron
- I dont know why this is a feature, blame APhatL
</details>
<details><summary>Powder Macro</summary>
	
- Hardstone Nuker minus the Hardstone Nuker
</details>

### Config Menu:

#### Explanation of Custom Item Macros:
	
Usage: `/usecooldown [milliseconds] [left]`

- Will create a new custom macro for the currently held item

- Use `/usecooldown 7000` to set a custom macro for Wand of Atonement

- Use `/usecooldown 100 left` to set a custom macro for Terminator

#### Explanation of Foraging Island Macro:

- Make sure the only 4 dirt blocks in range of the player are the ones to plant the tree on

- Make sure the tree can grow naturally:
	-  There is enough air above the dirt to let the tree grow
	- There are no solid blocks surrounding the tree

- Need to have in hotbar:
	- Treecapitator
	- Jungle / Dark Oak / Spruce Saplings
	- Enchanted Bonemeal
	- Fishing Rod
- Autopet rules: 
	- `When: You throw a fishing hook` -> `Equip Monkey`
	- `When: You gain Foraging XP` -> `Equip Ocelot`

- You can set up a redstone clock hooked up to a dropper system to allow for full automation

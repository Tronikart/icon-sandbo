### Warning!!
Currently doesn't work with Foundry VTT V10, I haven't personally updated yet and the Sandbox System Builder hasn't updated either, as soon as this changes, I'll update the system and probably notify on [Pilot NET](https://discord.gg/ZwnF2uAJ)'s icon-resources channel

## Foundry VTT ICON Character Sheets using Sandbox System Builder

Its based on [DMerceless'](https://gitlab.com/danielrbs/icon-sandbox-world/-/tree/main/) work, updated to 1.45 plus some additional stuff like:

- Wounds automatically reduce max HP
- Bloodied status automatically changes when  HP reaches 50% or lower
- Job sections appear as you level up and are eligible for them (lv. 4 and 8)
- Job section now has a table where to add the Job's Trait, to try and keep things organized and easy to access (clicking the desc icon will open a text area window)
- Limit Break section appears at Lv. 1
- Relics section appears at Lv. 2
- Tons of tips (and tooltips) found on the excel sheet are now here as well (Where to spend effort, what happens when invokin burdns, and so on)
- Inventory tab changed to Notes, this tab has some text areas and a list of Buffs, Blights and Statuses, each with their respective tooltip
- Skirmisher automatically makes your  Dash distance equal to your speed
- CSS to spice things up a bit (optional)

(Just in case you stumbled upon this wihtout knowing what ICON is, find it here https://massif-press.itch.io/icon)

## How to Install

1. Make sure you have Sandbox System Builder installed in Foundry VTT
2. After this, go to the Game Worlds tab and click on the Install World button at the button.
3. Locate the field for the Manifest URL at the bottom of the screen, paste the following URL and click Install

https://raw.githubusercontent.com/Tronikart/icon-sandbox/main/world/world.json

This will install a new world, launch it, and in there you'll find sheets for PCs, Foes and Camp. 

## Creating a new Actor

If you haven't used Sandbox System Builder before, the process is simple: 
1. Create an actor as you would
2. Open the sheet, you'll spot a "Default" dropdown menu
3. Select from that dropdown menu the desired type of sheet
4. Done!

If alerts pop up, try clicking the arrow button next to the dropdown menu to refresh it the sheet.

## Careful!

Don't touch the actors inside the Templates folder unless you know what you're doing!

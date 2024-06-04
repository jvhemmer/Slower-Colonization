# Slower Colonization
Slower Colonization mod for Europa Universalis IV.
Compatible with game version 1.37.*

Decreases the rate of colonization for both player and AI countries so that the map is not fully colonized by late game, making your campaign more historically accurate.

## Description
Ever feel like colonization is too fast? Want to export your save to Victoria 2/3 for a mega campaign but realize that there's not any land left to colonize? This mod is for you!

This mod reduces the rate of colonization by half (1/4 version [here](https://steamcommunity.com/sharedfiles/filedetails/?id=3259094213)) by applying a debuff to the "Global Settler Increase" modifier of each country. Countries are checked yearly, so there should be virtually no impact on performance. 

Due to a limitation of the game, modifiers cannot be dynamic. The solution is using a binary adder system which applies multiple modifiers of different values until the desired amount is reached. See below:

![Example](https://imgur.com/Pe42OXK.png)

Hovering over the Global Settler Increase in the Stability and Expansion tab shows the binary modifiers added. Note how the negative modifiers add up to half of what the positive modifiers add up to. This can also be verified for the AI by checking a province that they are currently colonizing.

![](https://i.imgur.com/j1ZZSWl.png)

Feedback is appreciated. If there is disagreement about colonization speed, I can make different versions with different rates (1/4 speed, 3/4 speed, etc.).

## Compatibility
Should be compatible with everything since it does not overwrite any game files.

Can be added and removed mid-campaign since nothing is added to the save file.

Not ironman compatible.

## Acknowledgements
This mod was only made possible due to u/Justice_Fighter which I believe is the developer of [MEIOU and Taxes](https://steamcommunity.com/sharedfiles/filedetails/?id=2630437525&searchtext=MEIOU+and+taxes]).

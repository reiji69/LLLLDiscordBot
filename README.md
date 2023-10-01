# LLLLDiscordBot
A Discord Bot to make LLLL player's life easy
I know a lot of these contents are WAY easier for users to understand and use if it has a GUI but my front-end skill doesn't even exist. Maybe if I got better I would come back and add it.


## Functions (Ranked at priority level)
* Card info checker

Checks a card's basic info, including name, rarity, type, preferred mood, basic stats for each level (smile, pure, cool, mental, and bp), special, active, and passive skill info, required materials for upgrading the card, special skill lv and active skill lv.
This would be the first module to be completed. From what I am thinking right now each card would have its own JSON file. All of these JSON files would be used to compile another group of CSV file that is used to access the information so that I can do this one time each update. Saves a bit of work if I can just create one file for each card rather than going into tons of CSV files to change stuff.

Ultimately I want this part being able to check the material required to level up from lvX to lvY for each skill/card.
* User Specific Calculators

Each discord ID should be able to log their current deck into the software, including the card levels, skill levels, LBs and SFLv so that an accurate bonus for their LGP bonus could be calculated. The user could also select a few cards into the upgrade pool and find a way to maximize mat efficiency. 

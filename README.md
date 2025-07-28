# Welcome to Sparkle, a Shiny Hunting tool!

This program requires Java Runtime Environment (JRE) to run. It can be downloaded here:

https://www.java.com/en/download/manual.jsp

## Install Guide:
- Click on the green "Code" button and select "Download ZIP".
- Unzip the folder with your extractor of choice.
- Open the folder, and click on Sparkle.jar to run the program!

## The Program

This program allows you to choose from Generations 2-8, along with a variety of Shiny Hunting methods, including:
- Random Encounters
- Soft Resetting
- Shiny Breeding (Generation 2)
- Masuda Method (Generation 4 and onwards)
- Poké Radar (Generations 4, 6 and 8)
- Chain Fishing (Generation 6)
- Friend Safari (Generation 6)
- Horde Encounters (Generation 6)
- DexNav (Generation 6)
- SOS Battles (Generation 7)
- Dynamax Adventures (Generation 8)
- Brilliant Pokémon (Generation 8)

Other options and features include:
- Choosing whether or not you have the Shiny Charm.
- Choosing whether or not you are hunting on multiple systems, as well as the amount of systems.
- Selecting any Pokémon from Generations 1-8 as your target Pokémon.
- Choosing whether or not you wish to use Streamer Mode (more below).
- Small Files (more below).

Once you have selected all of these prerequisites, the main GUI opens. The information on the GUI is as follows:
- Encounters: Displays the number of encounters you have had with your target Pokémon.
- +: Increments the Encounters counter by the number of systems you have entered. (by default, this is set to 1)
- -: Decrements the Encounters counter by the number of systems you have entered. (by default, this is set to 1)
- Odds: The odds of finding a Shiny Pokémon based on your chosen Generation and method.
- Time Elapsed: The amount of time you have spent hunting your target Pokémon.
- Binomial Distribution: Calculates the probability of finding the target Pokémon given the number of encounters and the odds.
- Pause: Pauses the timer if it is unpaused, and unpauses the timer if it is paused.
- Phase: Adds a face to the counter if you found a Shiny different from your target.
- Done!: Stops the timer, displays a congratulatory message, and disables the +, - and Done! buttons.

## Streamer Mode

Streamer Mode allows for a smaller screen by removing the +, -, Pause, Phase and Done! buttons, and instead instead opts to use key binds instead. This is perfect for if you wish to use Sparkle as a counter while streaming, as it will take up less room on your display.

The key binds for Streamer Mode are as follows: 
- Plus Key: + Button
- Minus Key: - Button
- Space Bar: Pause Button
- P Key: Phase Button
- Enter Key: Done! Button

## Small Files

Small Files are .txt files that update any time encounters are added or subtracted, and contain only the number of encounters, allowing for a more traditional display via OBS.

I hope you enjoy using the program!

## Special Thanks:
- The r/ShinyPokemon Discord
- Apache Commons (Math Library)
- msikma (PokéSprite)
- Jackster Productions (Pokémon GB Font)

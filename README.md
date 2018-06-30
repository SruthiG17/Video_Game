# Video_Game
# Merlin Bread: A platform game I created for my Intro to CS class final project.

All audio files must be downloaded onto the device that is trying to run this code.
The audio file for the main background music (variable name: music2) can be found here:
https://drive.google.com/file/d/1MoqM1-o2OS-mgEgxGe74SVpQPvqGu-IC/view
(NOTE: there have been some issues with using this audio file).

Time for each level is currently set at 30 seconds (variable name: how_long). I've found that 25 seconds is more difficult
and therefore more fun. the variable how_long is in this python file (once as global variable and once in the again function),
so both instances of the variable would have to be changed in order to play at a new set time when first playing the game 
and also when trying again.

The code for this game references two imports: pygame and gamebox. Gamebox is a python file created by my professor, Luther Tychonievich, for the purposes of simplying the use of the pygame import.

This project was completed with the guidance of Sean Gatewood (my class TA).

//

These are some brainstorming notes from when I created the idea for the game (Note: not all concepts were implemented)...

game  idea:
This will be a platform game. 
Main Character: Merlin the Wizard.
Story Plot: Merlin forgot to feed his dragon. Dragon is in dungeon.
Merlin needs to collect enough pieces of gluten-free bread to keep dragon happy.

Game Layout:
There will be three levels. Merlin will be traversing downwards (closer to the dungeon).
Each level will have bread pieces
to collect. There will also be goblins (Optional Requirement Met: Animation)
as obstacles for Merlin (Optional Requirement Met: Enemies). Each level must be completed with a certain time period
(Optional Requirement Met: Timer).A total of 50 pieces of gluten-free bread must be collected before reaching the dragon
(Optional Requirement Met: Collectables).There will also be regular bread. If Merlin accidentally collects
a piece of regular bread, he will lose two loaves of gluten-free bread.

Effects:
We will be including sound effects for when Merlin reaches the end of a level
and also for when Merlin collects bread/gets hit by an obstacle (Optional Requirement Met: Sound)

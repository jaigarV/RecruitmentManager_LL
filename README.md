# RecruitmentManager Legendary Lords customizations

This repository contains the code for a mod for the game Total War Warhammer 2, based on the original mod by DrunkFlamingo "Table Top Caps - Silent and Furious Edition". 

In this version, I increase the amount of special and rare units that Legendady Lords can field, while keeping the original values for the regular lords.

# Instructions to creat a mod

To create a mod out of the files in this repository, you need to use the RPFM program and create a new PackFile, which will include the folders and subfolders in "script" and "text", and add the "ui" folder from the original game that contains the images (binary files which are not handled well by git). Other folders from the repo can be omitted and I guess were left here by the creator to help him while developping the Lua code.



What follows is the original README by DrunkFlamingo:

# RecruitmentManager
Lua scripts for the Tabletop Caps mod on the Warhammer II workshop

Object model files are found in script/_lib/mod and have no game impact, nor track any data, without implementation.


Implementation files are found in script/campaign/mod, which set up listeners and helper functions to track and enforce unit caps.

Content is found in export helper files. 

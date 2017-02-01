# A study in modmerging

This is me messing around with WRECK and modmerger to see if I can make heads or tails of either, and possibly expand the WRECK injection system. No progress yet lol.

I tried to go through and comment/document some of the functions but didn't get very far.


I just had an alernate idea: Continue to work with the injection system, but rather than manually find injections:


Store injection as list of strings


store target file as list of strings


find object that matches a string (game_menu, script, troop, etc.)


split list at object, store first portion in a variable

find line matching target line

instert injection as appropriate in the list

recombine the two lists

write to file

this method is even reversible; just find injections and remove, as with imports in WRECKER


This works for adding lines to code at least. 

need to figure out replacement...

could use same method to comment out appropriate lines, although reversing this would be more difficult

Could just make this a separate WRECK Plugin Installer


Hell I could make it a general OSP kit installer

I'll see if anyone on the forums would be interested in using it, possibly even helping out. I don't think it'll be horribly complicated though
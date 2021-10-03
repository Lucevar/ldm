				Expansion Delay
				By Half11

Version: 1.1



=========
Contents
=========
1.    Description
2.    Requirements
3.    Installation
4.    Distribution permission
5.    Changelog
6.    Credits


===========
Description
===========
This mod fixes Bethesda's overly enthusiastic expansion hooks by delaying the Dark Brotherhood attacks (for Tribunal) and limiting intrustive dialogue topics to a few NPCs (Bloodmoon). Bethesda probably assumed that everyone would be high enough level when the expansions came out and didn't bother to account for new players and characters.

Note: You might know a similair mod by me called Better Expansion Implementations. I got feedback that such an essential mod should not be burried in my Misc Mods page, so I have decided to give the mod its own page, a name that is easier to remember and updated some dialogue filters.


Tribunal:
- You won't be bothered by assassins until pretty far into the main quest. *SPOILER ALERT* You won't be attacked until you have been named Nerevarine by at least one Ashlander tribe. An early assassin attack doesn't make sense lore-wise. Almalexia straight up calls the PC Nerevarine. Also, Helseth wouldn't plan an assassination on a no-name. *END OF SPOILER*
- The expansion forces you to start the Tribunal quest, to be no longer bothered by assassins when you rest. To prevent this forced feeling I made the stream of assassins stop earlier, at the time a guard tells you the assassins are likely members of the Dark Brotherhood ("A guard has told me that my attackers were likely members of the Dark Brotherhood, and that I have been targeted for assassination. He suggests I speak with Apelles Matius in Ebonheart for more information."). At that point (TR_dbAttack 30) you have all the information you need, and the possibility to start the Tribunal questline has been introduced in a not too compelling way. You no longer have to interrupt your adventures for a trip to Ebonheart to stop the attacks. Lorewise the Dark Brotherhood attacks should start during a certain point in the Vvardenfell mainquest. It would be awkward to be forced to start the Tribunal mainquest at this point.
- *SPOILER ALERT* A check was added if you killed Dagoth Ur, in case you do the main quest the backdoor way, and are never named Nerevarine by any Ashlander tribe. *END OF SPOILER*
- Farming the assassins is still possible (if that's your thing). Just don't talk about the attacks to guards.

Bloodmoon:
- You won't be bothered by the dialogue that Bloodmoon introduces until level 6 (just like Bethesda did with Tribunal expansion on the Xbox). This was necessary to prevent the new dialogue from blocking other dialogue at low levels.
- Now only one random generic Imperial guard has his son send to Solstheim. I found it hard to believe that Jonus Maximus, being a high ranking legionary, had no idea why his son was sent to Solstheim in Illy's Solsteim Rumour Fix.
- What I have taken over from Illy is binding the other rumour ("I heard there...north of Vvardenfell.") to the Agent class. This was done to prevent every NPC from having the Solstheim topic.
- If the player somehow missed the second quest update (BM_Rumors 50) after hearing about Solstheim for the first time (BM_Rumors 10), Scouts can also update your journal ("That's the frozen...transportation in Khuul."). The permanent topic about getting to Solstheim is also tied to the Scout class now ("A terrible place...any reason to go.").
- Fixed dialogue filtering, so that NPC's that aren't supposed to have no dialogue topics at all (NoLore), won't have topics in their dialogue box.
- Now you'll actually have a chance to see the Dunmer rumour ("I've been told ...is beyond me.") regarding Solstheim on Vvardenfell. Previously it was highly unlikely to come across this rumour.
- *SPOILER ALERT* Louis Beauchamp (NPC outside Ald'ruhn Mages Guild) will be disabled until you started the Bloodmoon main quest. This was done to prevent new players from getting spoiled by his quest, sending them to Solstheim. *END OF SPOILER*


=============
Requirements
=============
Morrowind
Tribunal
Bloodmoon


==========
Installation
==========
Copy the Expansion Delay.esp file into your Morrowind\Data Files folder. Activate the mod in the Morrowind launcher.


====================
Distribution permission
====================
You are not allowed to convert/alter/modify/translate/improve/commercial benefit/use assets from or reupload this mod to other sites under any circumstances, without getting my permission to do so first. If you are interested in using this mod (in part or in whole) in your own mod please contact me first. I'm pretty open about people using my stuff as a modder's resource for creating their own unique mods, but I would need to see if it is along my vision or even improves on it, before I can give permission.

Please do not compile and release my mods in a larger mod without permission. I am not a fan of people trowhing cheap rips of my mods of mine (with or without small adjustments) in mod packs or compilation mods. My mods are subject to updates and expansions on a mere whim, so I want to keep track of comments and see if users have bug reports or feedback for the mod in question. This won't be possible if people only knew my work through a sort of compilation.


==========
Changelog
==========
Version 1.1 [June 21st, 2020]
• Changed the one random non-Legion Imperial having his son send to Solstheim to a random generic Imperial guard. There were quite a few prominent non-Legion Imperial NPC, which made for some funny scenarios.

Version 1.0 [February 10th, 2020]
• Initial release.


=======
Credits
=======
Illuminiel for the orginal Illy's Solsteim Rumour Fix which inspired this mod.
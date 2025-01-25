# game

Project
    _    ____   ____ ___ ___   _____                      
   / \  / ___| / ___|_ _|_ _| |_   _|____      _____ _ __ 
  / _ \ \___ \| |    | | | |    | |/ _ \ \ /\ / / _ \ '__|
 / ___ \ ___) | |___ | | | |    | | (_) \ V  V /  __/ |   
/_/__ \_\____/_\____|___|___|   |_|\___/ \_/\_/ \___|_|   
|  _ \  ___ / _| ___ _ __  ___  ___                       
| | | |/ _ \ |_ / _ \ '_ \/ __|/ _ \                      
| |_| |  __/  _|  __/ | | \__ \  __/                      
|____/ \___|_|  \___|_| |_|___/\___|  
.
.
Create a game or tool using Claude. Document the process using best practices on Github.
.
.
-----

Tools Used
ChatGPT
Claude
Pencil/Paper
Figma
Rosebud.ai game maker (exploration that didn't really work)

-----

Project Video

----

Sketches



-----

Learning/Impact
I wasn't chaining my prompts very efficiently at the start. I used a prompt engineerGPT and tried to create a massive prompt that clearly bit off more than it could chew. This also had the unintended effect of taxing claude with a long message chain and burning through my usage limit really quickly. 

To better manage future projects:
Create Project folder in Claude
Define master plan and upload it to project knowledge
Chunk it into smaller pieces, each in their own chats
	Layout/Grid
	Path Builder
	Tower Placement/Bank
	Enemies/Combat
	Fail/Success States



-----

Bonus: Edits outside Claude

-----

Initial Thoughts 1/24/25
I'm definitely drawn towards making a game. I think back to all the flash games I would play online growing up and I think it would be cool to create something as an omage to those games. So I'm exploring a few different concepts that I'll take into sketching to refine.

Escape Room Game
Tower Defense
Fruit Ninja

I'm not really wanting to do a platformer or fighting game. Currently I'm leaning towards Tower Defense with Escape Room as a possible extra credit option. 

I'm thinking that the form factor should be mobile, but maybe I should try to build in a desktop to mobile breakpoint. 
	I'm going to use a mobile-first design approach.

1/25/25
So I've been working on sketching things out. My first thought was to create a control interface similar to the ones I've seen on emulators like Lemuroid. I'm second guessing that a little bit. If I have a breakpoint for the desktop then the control scheme becomes unnecessary because the user will be using a mouse. So maybe I should eschew the emulation housing for a more tap based solution?

Ive got a good idea of what I want it to look like (see sketches section above), I'm just having issues finding alignment. 

Now that I'm at a stage where I'm getting it to look closer, but the functionality is just not there.

I'm creating a "level builder" mode that will allow me to actually build the level, but then allow the user to build custom levels on their own. Adding it to the menu. 

I've made a lot of progress! Got the layout pinned down (mostly), the level builder is functional, it connects to the main play field, you can place towers, and an enemy spawns after a countdown.

I'll pick back up later. 

	Reduce countdown to 3 seconds.

	Enemies reaching the path should subtract a life from the counter. The counter reaching zero should trigger a fail state screen that offers the user an option to retry the level from the beginning or quit.

	The towers should attack enemies on the path in adjacent cells. The attack should projectiles in the form of "~". There should be an internally consistent math that subtracts health from the enemies. it should take between 3-5 attacks to defeat an enemy. Attacks should occur at regular intervals.
	
	Towers should cost $50, drawing from the bank. Players must have sufficient funds to purchase towers. Defeating an enemy is worth $25.
	
	The enemies should come in 5 waves of between 6-10 enemies.

----
Thanks for tagging along.
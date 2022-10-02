# The-Fault-in-Our-Mars
video game
Hack mit 2022
Mars survival game
Actual murder–murder mystery
Day/night cycle, vision restriction
Vocal commands–only input is vocal command to direct players to locations and make adjustments 
Puzzle games incorporated into gameplay

GOOGLE DRIVE LINK FOR EXE:
https://drive.google.com/drive/folders/1BN-0HfIZPDAG4qHp5xtOLEE_kcXl0T0o?usp=sharing

KEYWORDS
        actions.Add("go to the ship", GoToShip);
        actions.Add("go to ship", GoToShip);
        actions.Add("spaceship", GoToShip);
        actions.Add("space ship", GoToShip);
        actions.Add("go to the spaceship", GoToShip);
        actions.Add("go to base", GoToBase);
        actions.Add("go to the base", GoToBase);
        actions.Add("go home", GoToBase);
        actions.Add("go to the solar panels", GoToPanels);
        actions.Add("go to the panels", GoToPanels);
        actions.Add("go to panels", GoToPanels);
        actions.Add("yes", Yes);
        actions.Add("yeah", Yes);
        actions.Add("i hear you", Yes);
        actions.Add("sure", Yes);
        actions.Add("affirmative", Yes);
        actions.Add("no", No);
        actions.Add("negative", No);
        actions.Add("nah", No);
        actions.Add("no i don't", No);
        actions.Add("I don't hear you", No);
        actions.Add("stay", Stay);
        actions.Add("stay in the base", Stay);
        actions.Add("investigate", Investigate);
        actions.Add("investigate outside", Investigate);
        actions.Add("somewhere else", GoToSupply);
        actions.Add("somewhere", GoToSupply);
        actions.Add("another place", GoToSupply);

Mars man john green
He be in the mars base
Mars base broken
He wakes up canny find anyon1
Tries contacting home base
Comms bad
Home base tells him what to fix
Try to solves the mystery of where his buddies went
Finds one of the corpses in a cave


MORE STRUCTURED NOTES BELOW
Sarah’s idiosyncratic notations:
PLY: Player
AST: the stranded astronaut
IMP: Imposter, the antagonist, the bad guy, whatever you’d like to call them
AI: AI, the only comms method that PLY can use
BAS: base, the base on Mars


Set Up:
Control Panel: Game displays a control panel with the majority of the panel being the Camera, the scene of AST in BAS; There could be a text display field that displays WHAT THE AI TELLS AST (this detail will become important later). the rest could be a collection of Meters and Buttons
Camera: 3rd-person, the scene of AST in BAS, in top-down view (as if viewing down from a satellite above BAS)
Potential additional feature: switch of camera to 1st-person view (as if viewing through a camera installed on the helmet of AST)
[OPTIONAL] Meters: bars that display levels of multiple metrics
Potential ones can include: trust between AST and PLY, vitals (health, mental stability), resources (oxygen supply, electricity, fuel)
[OPTIONAL] Buttons: 
Potential ones can include: a button to start/stop vocal input for PLY
More potential idea: controlled by AI, will stop working after a point as AI takes control of PLY

BAS: the main map of the game, includes many Locations, Devices, and Puzzles
Locations: generally rooms or distinct areas in BAS. Each has a distinct, specific name, so that vocal commands can be used to move the player to each location
Devices: devices in locations PLY can ask AST to interact with. AST can only interact with a device after they arrive at a Location (this allows same types of devices exist in different locations, potentially enabling some puzzle solving or completion of tasks)
Puzzles: a type of task. PLY needs to direct AST to complete puzzles and/or tell AST the answer to the Puzzle to solve it.

Basic Structure:
POV: 3rd-person in terms of AST, but it’s actually fundamentally 1st-person with PLY as the comms operator in Huston (or some other arbitrary NASA control center or something on earth)
(Apparent) Goals: 
[1st Priority] Help AST survive
[2nd Priority] Save AST (retrive AST from base with a ship–the ship can just be a final task where AST need to move to a designate location outside of base after a certain length of time after the start of the game)
[3rd Priority] Investigate murder mystery (find out why other astronauts died, why things are missing/sabotaged, who is behind all this, etc.)
***NOTE: although they are categorized in terms of “priorities”, PLY can choose which goal/tasks they want to direct AST to complete first; It can totally be a mash-up of all 3 categories
Ways to Achieve the Goal: 
***NOTE: completing tasks are not the major objective of the game; The game, with its Major Additional Features/Twists, should be more like storytelling. The tasks are simply a way to give AST and PLY an initial purpose while giving cues for storytelling
Complete TYPE 1 Tasks (corresponds with 1st priority), which could be something like
Fix oxygen tanks
Find food in base
Fix water purification systems
Complete TYPE 2 Tasks (corresponds with 2nd priority), which could be something like
Fix/develop navigation devices to help rescue ship arrive and land
Fix other communicative devices between the rescue ship and ASTTravel to the location the rescue ship is landing
Complete TYPE 3 Tasks (corresponds with 3rd priority), which could be something like
Eploring Locations in BAS
Exploring outside
Investigate corpses
Installing cameras?? 
Major Additional Features/Twists (for more details, see Storytelling):
At certain intervals (or random?), AI will prompt PLY to initiate conversation abut personal details with AST (or AST can spontaneously initiate conversation with PLY)
Vocal recognition will convert and store these personal details for when AI takesover as IMP
Increase trust points after each conversation (?)
After a certain point (completion of a certain number of tasks? Cumulation of a certain number of trust points? Completion of a certain number of vocal inputs?), AI will Twist commands from PLY to AST
Twisted commands leads to failure of tasks
Could be a wrong answer to a puzzle (probably easiest way in terms of coding), or a wrong point to connect in a tasks, or a wrong object to choose for a task
PLY will be able to see that commands are Twisted. This is why it helps to have a text display field in the Set Up of the control penal as mentioned earlier
This make sure PLY understands that it’s the AI that’s interfering, not that AST is not following their instructions
After the AI twists enough commands and cumulates enough failed tasks (another point whose exact definition we may need to decide on), it takes over and starts communicating with AST as the IMP of the PLY
Text display field display pre-written scripts that sabotages the rescue, misleads AST, and/or leads AST to their death (the goal of IMP)
Text display field display generated messages using PLY’s personal information gathered during conversations that “convinces” AST to do these actions that sabotages the rescue and leads to their own death
NOTE: here “convince” is just a way to describe the nature of these messages. It has no actual effect on elements in the game, as AST is programmed to do whatever AI tells them to do.
Main purpose of these messages is to confuse and scare PLY an leads to the point of making this game
The Point of Making This Game:
Let people be aware of one possible scenario of AI if AI is designed/used to do bad things
In this game, the AI is designed by IMP to sabotage the mission and kill AST and other people
Other points..???


Project Checklist:
Complete set up
Complete art & design
Complete vocal recognition/voice to text programming
Complete location set up
Solar panel
Fix solar panel
Get airdropped supplies
Rocket workshop station




Storyline:
Player is comms operator in Houston
Direct the stranded astronaut to investigate/explore/prepare for rescue
The AST is the only one who survived some kind of disaster caused by the IMP

Resources:
https://docs.unity3d.com/Packages/com.unity.scripting.python@2.0/manual/index.html
https://forum.unity.com/threads/recommendation-on-emotion-recognition-with-unity.911066/


Element ideas:
IMP sabotages life support, resources, comms, devices, 
IMP impersonate PLY, slowly overtaking 
IMP takes over and directs the 
AST/IMP can initiate chat with PLY to gather personal information (tie into privacy and banes of social media)
Can have meters on screen measuring trust/friendship, oxygen, etc. 
Incorporate these bars 

Art/Design pieces needed:
Items:
Characters:



Map/map layer components:
Locations:
Maps:


Puzzles:

Script:

>> A computer monitor fills your screen. The screen displays live footage of an astronaut on Mars. The astronaut stands at the center, in front of the damaged base. 

Text appears at the bottom of the monitor.
    Astronaut: Houston. Houston, do you copy?

Text, in a different color, appears at the top of the monitor, perhaps alongside the icon for the 
Digital Assistant: A response is needed. Please sep




AI: (text to speech, Salli, Female) https://voicemaker.in/
Voice distortion: https://voicechanger.io/voicemaker/#!/{%22effects%22:[{%22name%22:%22oldRadio%22,%22params%22:{%22distortion%22:25,%22magnitude%22:0.26}},{%22name%22:%22pitchShift%22,%22params%22:{%22shift%22:-0.64}}],%22version%22:1}

The script we ends up doing:
A1: Martian pioneer to ground station…
Yes: A2
No

A2: We… no, I, I could not find anyone in the base after I woke up. The entire building is empty. Everyone except me is missing. Everyone!! Ahem, excuse me. What are the instructions? What are the instructions, ground station? Should I stay in the base or investigate outside? Over.
A2b, Stay in base: A3
A2o, Investigate outside: A4

A3: Huh… I am beginning to feel faint. What is going on, ground station? It is getting so… so difficult to breath. [DEATH]

A4: It appears that someone damaged the life support for the building. No wonder it feels truly suffocating in there. It seems I cannot stay in the base for long–should I move on to check the systems of solar panels or the Martian Pioneer spaceship?
A4sp, Solar panels: A5 (Please look into the solar panel systems. Make sure that they are functioning normally.)
A4sh, Spaceship: A6 (Please look into the Martian Pioneer spaceship. Make sure that it is functioning normally.)
No response…???

A5: [Insert task/puzzle??] I cannot believe this. How come the panels are covered in so much dust? It’s only been one day… or has it…? Regardless, it is very strange. [Short pause]. Oh, I think this may be the reason–the auto-cleaning system on the solar panel is turned off. Maybe someone forgot to turn it back on after a systems check? Hm. There we go–I turned it back on. Should be good now. Shall I go check on the spacecraft next, or shall I go somewhere else?
A5s, Spacecraft: A6
A5e, Somewhere else: A7

A6: [Insert task/puzzle??] This is very weird. The spaceship’s gate system is glitching. I remember doing maintenance on it just yesterday……or was it yesterday…? Anyhow, it is very strange that it’s broken now. [Short pause]. Hmm–it shows here that the lock from inside the capsule is activated. Maybe someone forgot to turn it back off after a systems check? Hm. There we go–I turned it off with my key. Should be good now. Shall I go check on the solar panel systems next, or shall I go somewhere else?
A6s, Solar: A9
A6e, Somewhere else: A8 (?)


A7: similar stuff as A6, but offers the option to check airdrop location and the option of going somewhere else (all somewhere else in A5, A6, A7, A9 actually refers to the cave)

I’ve collected some things from the supply drop. Should I go to the solar panel, spaceship, or somewhere else?

Somewhere else: A8


A8: death clip in cave


A9: similar stuff as A6, but offers the option to check airdrop location and the option of going somewhere else (all somewhere else in A5, A6, A7, A9 actually refers to the cave)





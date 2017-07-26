# MvBot v1.3.1, 2017.07.26
Professional bot for Medivia v2.0

Program supports both Medivia clients: OpenGL and Directx. Small CPU usage has always been in the forefront so can easy start 10+ bots on 2GHz.
Main idea of this software come when Me and my firends needs some runnes for hunting. Controling a few accounts manually in one time was pretty hard and offen some person wants to kill my character. Now using MvBot you are able to autome most of less or more advanced actions.  

Let's see what exactly you can do:

- Lighthack, AntiIdle, FoodEater;
- Reload Ammunition, Gold Stacking, Fishing;
- Hold Target, Spears PickUp, Dashing;
- Hold Mana Shield, haste, invisible;
- Cure burning, poison or electricity;
- Heal you and your friends with runes or spells;
- Dring mana fluids, advert your buy or sell offers on all channels!
- Make runes, ammunition or just burn mana;
- Automatic logout, step to safe place or pause bot on danger!
- Hotkeys shooting runes with players and monsters. Also build in equiping and droping hots;
- Smart alarms sytem play sound when danger come to screen or your health percent is low;
- ScreenShoots taker make some pictures on your death or advance;

# Update v1.2.1

- Bug Fixes:
	- Food Eater sometimes stop eating food.
	- Runemaker logout if no food or blanks.
	- Items reader now read all items properly.
	- Hotkeys drop variable x, Use item with creature.


- Added or Improved:
	- Injector to last active Game window, minimize to Tray and close bot if game process not exist.
	- Modules status bar.(Enabled/Disabled)
	- Mod(Tools): Re-Ammo, refill ammunition to arrow slot.
	- Mod(Tools): Gold Stack, auto stack Gold Coins in all containers.
	- Possibility to set own delay on Healer and Hotkeys modules. (Hotkeys.min=0ms, Healer.min=100ms)
	- Mod(Runemaker): Destination Mana Burn if user just wanna train magic level.
	- Mod(Runemaker): Auto stack created ammunition in container. Drop on ground [x, y] if out of capity.
	- Mod(Runemaker): Player logout, auto relogin, reopen backpacks and Last detected player label.

# Update v1.2.2

- Added or Improved:
	- Mod(Runemaker): Player show diagnostic information button.
	- Mod(Tools)[Fishing]: Possibility to fishing with capity limit. (unfortunately working only with visible water fields)
	- Mod(Tools)[Hold Creature]: Auto hold follow or target. (Set green/red square is disabled to avoid crash client)
	- Mod(Tools)[Spears Pickup]: Pickup spears 1sqm around your character.
	- New Mod(Chatter): Possibility to say messages on different channels.
	- New Mod(Alarms): Play sound or flash application if any condition meet requires.

# Update v1.2.3

- Bug Fixes:
	- Now alarms working with a single object, creature detection do not block other conditions.
	- Increased delay in hold position to avoid dash 2 squares.
	- Fixed timers in relogin/reconnect functions.

- Added or Improved:
	- New Mod(Screen-Shoter): Take a screenshoot on special condition.
	- Mod(Alarms): New sound for each alarm condition.
	- Mod(Runemaker)[Player]: Force step if player on screen.
	- Gui(Main): Change client title on current logged character and hide gui to tray if game inactive.
	- Mod(Tools): Numpads dash. While Num Lock is active keys stay walking directions.	

# Update v1.2.4

- Bug Fixes:
	- Close bot in tray now works ok.
	- Mod(Chatter): Edit message now replace index than delete and create new.
	- Mod(Tools)[Dash]: Added min delay 10ms to avoid crashing _Send_Packet() func.
	- Mod(Runemaker)[Destination:LeftHand]: Now runemaker will deposit rune to last used backpack or just take with empty slots if last is full.
	- Mod(Runemaker)[Relogin:OpenBackpacks]: Improved function to open backpack if ids are this same. When Backpack will miss(user deposit or smth) func break loop on last avaiable to open.
	- Mod(Hotkeys)[Use On Yourself]: Fixed bug with drinking flasks.
	- Mod(Alarms)[Hold Position]: Set priority=1 to pos keeper works with other conditions.

- Added or Improved:
	- Disabled function to hide gui when Client window inactive (bugged with other mod pannels, will restored later)
	- Added Safe List to Mod(Alarms) and Mod(Runemaker).
	- Increasing delay to 200ms in th most of modules.
	- Optimized functions in all modules to eat less CPU. Decreasing around 250%.
	- Added prototype of Targeting. Creature reachable won't work now.

# Update v1.2.5	

- Bug Fixes:
	- Mod(Healer,Hotkeys)[Use On YourSelf]: fixed drinking vials.
	- Mod(Hotkeys)[With Crosshairs]: Renamed to "Use Object". That was a misstake while creating combobox.
	- Mod(Tools)[Fishing]: Fixed bug with error ~10k line.
	- Mod(Tools)[Hold Creature]: Disabled red square to stop debuging.

- Added or Improved:
	- Mod(Healer)[Heal Friends]: added connection to Friends List.txt(removed priority) also added min mana need to heal.
	- Mod(ScreenShooter)[Creature]: will miss creatures in Friends List.txt.
	- Implemented new map/battle structure reader function. Fast and smooth. (IMPORTANT! MAY SOMETIMES CRASH CLIENT WHEN RELOGIN. PLEASE REPORT THIS CONDITION.)
	- Mod(Targeting): Improved creature reachabilty.
	- Improved _Self_WalkTo() function to reach possible position if source is blocked.
	- Added Mod Walker with a few simple actions.

# Update v1.3.0	

- Bug Fixes:
	- Fixed bug with walker stuck when target out of screen.
	- Mod(Walker)[Tool][Machete]: Re-worked function.
	- Mod(Walker): Re-build _Self_WalkTo function. May work a little strange but shouldn't crash client.
	- Mod(Targeting)[Keep Realistic,Face,Digitional]: Check function now reading small array with: Holes, Stairs and Fields(Fire,Pox,Energy) and do not walk on this titles.


- Added or Improved:
	- Improved reading Nodes & Stands when Targeting is Enabled.
	- Removed $WS_MOSTTOP condition from all Mods (miss Walker). Added Exit & Minimize buttons.
	- Mod(Walker)[Action][Extra]: added Switch Label action.

# Update v1.3.1	

- Bug Fixes:
	1. Fixed bug with reconnect (blocking ip connection on save server) 
	2. Small bug with Tray Icon.

- Added or Improved:
	- Added Mod(Save & Load Settings). Now you are able to save your configs in txt file. Warring! Reopen bacpack will not saved.
	- Implemented server license veryfication.
	- Disabled Mod(Cavebot) until memory bugs with attack creatures and walking long distance will be fixed.

Contact: hxbot1@gmail.com

Regards,

Ascer

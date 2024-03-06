The Core Lite v2.3
==================

### Table of Contents
* [The Core Lite v2.3](https://github.com/bobo38/TheCoreLite/blob/master/README.md)
  * [Repository description](https://github.com/bobo38/TheCoreLite/blob/master/README.md#repository-description)
  * [Resources](https://github.com/bobo38/TheCoreLite/blob/master/README.md#resources)
  * [Acknowledgments](https://github.com/bobo38/TheCoreLite/blob/master/README.md#acknowledgments)
  * [TheCore Lite features](https://github.com/bobo38/TheCoreLite/blob/master/README.md#thecore-lite-features)
* [TheCore Lite Command spirit](https://github.com/bobo38/TheCoreLite/blob/master/README.md#thecore-lite-command-spirit)
  * [Unit keys](https://github.com/bobo38/TheCoreLite/blob/master/README.md#unit-keys)
  * [Building Consistency](https://github.com/bobo38/TheCoreLite/blob/master/README.md#building-consistency)
  * [Unit Production](https://github.com/bobo38/TheCoreLite/blob/master/README.md#unit-production)
  * [Rapid Fire and Precision keys](https://github.com/bobo38/TheCoreLite/blob/master/README.md#rapid-fire-and-precision-keys)
* [TheCore Lite User Interface keys](https://github.com/bobo38/TheCoreLite/blob/master/README.md#thecore-lite-user-interface-keys)
  * [Function keys](https://github.com/bobo38/TheCoreLite/blob/master/README.md#function-keys)
  * [Other tips](https://github.com/bobo38/TheCoreLite/blob/master/README.md#other-tips)
  * [Moved out of the dense keycard and Function keys](https://github.com/bobo38/TheCoreLite/blob/master/README.md#moved-out-of-the-dense-keycard-and-function-keys)
* [TheCore Lite Macro groups](https://github.com/bobo38/TheCoreLite/blob/master/README.md#thecore-lite-macro-groups)
  * [History](https://github.com/bobo38/TheCoreLite/blob/master/README.md#history)
  * [Nexus/CC/Hatch group = W](https://github.com/bobo38/TheCoreLite/blob/master/README.md#nexuscchatch-group--w)
  * [Production group (or inject queens) = Q](https://github.com/bobo38/TheCoreLite/blob/master/README.md#production-group-or-inject-queens--q)
  * [Utility group = 1](https://github.com/bobo38/TheCoreLite/blob/master/README.md#utility-group--1)
  * [Trash group key = Grave](https://github.com/bobo38/TheCoreLite/blob/master/README.md#trash-group-key--grave)
  * [Group display](https://github.com/bobo38/TheCoreLite/blob/master/README.md#group-display)
* [TheCore Lite Group/Cameras modifiers](https://github.com/bobo38/TheCoreLite/blob/master/README.md#thecore-lite-groupcameras-modifiers)
  * [History](https://github.com/bobo38/TheCoreLite/blob/master/README.md#history-1)
  * [Groups and mouse synergies with Ctrl and Ctrl+Shift](https://github.com/bobo38/TheCoreLite/blob/master/README.md#groups-and-mouse-synergies-with-ctrl-and-ctrlshift)
  * [Easier cloning through Shift+Alt](https://github.com/bobo38/TheCoreLite/blob/master/README.md#easier-cloning-through-shiftalt)
  * [Shift/Control and camera synergies](https://github.com/bobo38/TheCoreLite/blob/master/README.md#shiftcontrol-and-camera-synergies)
* [Use case scenarios](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-scenarios)
  * [Use case: Start Sequence](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-start-sequence)
  * [Use case: expansions cameras](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-expansions-cameras)
  * [Use case: send worker back to resource gathering after queued commands](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-send-worker-back-to-resource-gathering-after-queued-commands)
  * [Use case: army production + rally point (optional warp-in pylon)](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-army-production--rally-point-optional-warp-in-pylon)
  * [Use case: warp-in pylon](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-warp-in-pylon)
  * [Use case: TheCore Lite inject initiate](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-thecore-lite-inject-initiate)
  * [Use case: Telegraph inject (Backspace family)](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-telegraph-inject-backspace-family)
  * [Use case: TheCore inject](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-thecore-inject)
  * [Use case: Camera creep spread](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-camera-creep-spread)
  * [Use case: hatching eggs](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-hatching-eggs)
  * [Use case: zerg macro routine](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-zerg-macro-routine)
  * [Use case: Easy MULE/Chronoboost](https://github.com/bobo38/TheCoreLite/blob/master/README.md#use-case-easy-mulechronoboost)
* [Further optimizations](https://github.com/bobo38/TheCoreLite/blob/master/README.md#further-optimizations)
  * [The Control key placement](https://github.com/bobo38/TheCoreLite/blob/master/README.md#the-control-key-placement)
  * [Other possible tweaks](https://github.com/bobo38/TheCoreLite/blob/master/README.md#other-possible-tweaks)
* [Changelog for the code](https://github.com/bobo38/TheCoreLite/blob/master/README.md#changelog-for-the-code)

## Repository description
This is the Github repository for TheCore Lite Starcraft2 bindkeys.

### How to get TheCore Lite installed:
* Get the .SC2Hotkeys
  * Download a full .zip of latest stable release [here](https://github.com/bobo38/TheCoreLite/releases) – low amount of unbounds possible due to Blizzard updates
  * Download latest version for your keyboard layout, browsing the repository and [download the raw file content](https://raw.githubusercontent.com/bobo38/TheCoreLite/master/Reference/getTheCoreLite.jpg) - may be inconsistent
* Drop the file in the proper directory on your computer, if you don't find it, please read [TheCore install instructions](https://docs.google.com/document/d/10auUgrpf-umdQwcwrt_GXmBc3I5xRVte3YCGnMU_fcU/edit)

### Project goals
* keep as much consistency as possible with legacy "TheCore Lite" for [Commands] section
  * optimization over time, please report [bugs and possible enhancements](https://github.com/bobo38/TheCoreLite/issues)
* allow easy 2-keys-based macro mechanics
* get rid of bad habits and develop sane mechanics
* encourage camera keys usage for:
  * rally points
  * warp pylons
  * creep spread

### Coverage and checks
* no keys conflicts across supported modes (please report any that you find)
  * WoL HoTS LoTV multiplayer
  * Campaigns (WoL HoTS LoTV Nova)
  * Coop
* pass TheCore standards
  * keys supposed to be the same, or inherited (multi-racial support)
  * delivered in a set of supported keyboard layouts
  * it passes all the new introduced "seed" checks

## Resources

Beside this README.md file,
some graphic resources are available in Reference directory.
Please download the following .pdf file:

* [TheCore_Lite.pdf](https://github.com/bobo38/TheCoreLite/raw/master/Reference/TheCore_Lite.pdf)

Online community help, please follow netiquette:
* [TheCore Lite Discord channel](https://discord.gg/CeC7MEG)

Legacy resources:
* [historical Master Spreadsheet](https://docs.google.com/spreadsheets/d/1v1gTY9suNstl6KoYQ0zIA8_dIBAJ9COmdtbQ1AEuxV4/edit?pref=2&pli=1#gid=56)
* [TheCore Lite thread on teamliquid.net](http://www.teamliquid.net/forum/sc2-strategy/333891-thecore-lite-advanced-keyboard-layout)

Other resources:
* [NeoBlade's video (May 2017)](https://www.youtube.com/watch?v=y5Gw3BQfC_g)
* [Feedback on NeoBlade's video (May 2017)](http://www.teamliquid.net/forum/viewpost.php?post_id=26542923)
* [NeoBlade's latest video (November 2018)](https://www.youtube.com/watch?v=GaeF9TVsZRU)
* [Feedback on NeoBlade's video (November 2018)](https://www.teamliquid.net/forum/viewpost.php?post_id=27204690)

## Acknowledgments

Loads of thanks to:
* TheCore project, of whose repo this is a fork, and all the accumulated work over the years
* JaKaTaK, the originator of the first TheCore Lite version
* BeedeBdoo, who explained me the arcanes of TheCore, and datamined command card conflicts
* MilExo, who reviewed extensively the Protoss aspect of TheCore Lite

## TheCore Lite features

#### Implemented TheCore tips
* [Consistency across all races](https://github.com/bobo38/TheCoreLite/blob/master/README.md#thecore-lite-command-spirit)
* [2 keys macro groups](https://github.com/bobo38/TheCoreLite/blob/master/README.md#thecore-lite-macro-groups)
* [Control group and camera modifiers with good synergy with UI](https://github.com/bobo38/TheCoreLite/blob/master/README.md#thecore-lite-groupcameras-modifiers)
* [Easy access to groups, cameras, basic commands and spells](https://github.com/bobo38/TheCoreLite#unit-keys)
* [RapidFire alternates](https://github.com/bobo38/TheCoreLite#rapidfire-keys)
* [Zerg extensive select larvae alternates](https://github.com/bobo38/TheCoreLite#zerg-larvae)
* [Center on selection + add to hatch+CC/Nexus](https://github.com/bobo38/TheCoreLite#use-case-expansions-cameras)
* [Rotate camera](https://github.com/bobo38/TheCoreLite#fight-against-invisible)
* [Control cameras](https://github.com/bobo38/TheCoreLite/blob/master/README.md#additional-cameras-alternates-on-control)

#### TheCore Lite extras
* [Control(+Shift)+Tab as Army selection](https://github.com/bobo38/TheCoreLite#select-all-army-on-tab-key)
* [Shift+Q+W select prod buildings and jump to rally point](https://github.com/bobo38/TheCoreLite#use-case-army-production--rally-point-optional-warp-in-pylon)
* [Shift+Q+W+Space TheCore Lite inject initiate](https://github.com/bobo38/TheCoreLite#use-case-thecore-lite-inject-initiate)
* [TheCore Lite telegraph inject (backspace family)](https://github.com/bobo38/TheCoreLite#use-case-telegraph-inject-backspace-family)
* [Utility group and creep queen mechanics](https://github.com/bobo38/TheCoreLite#utility-group--grave)
* [Shift+Alt easy cloning](https://github.com/bobo38/TheCoreLite#easier-cloning-through-shiftalt)
* [RapidFire caster split](https://github.com/bobo38/TheCoreLite#high-templar-group-example)
* [RapidFire static defence](https://github.com/bobo38/TheCoreLite#rapidfire-static-defence)
* ~~[Quick Camera](https://github.com/bobo38/TheCoreLite/blob/master/README.md#quick-cam)~~

----------------------------------------------------------------------------------------------------------------------

TheCore Lite Command spirit
===========================

In this section, keys used to describe command mapping are using US QWERTY standard keyboard layout.
This applies as well to the groups and cameras mapping in the rest of the document

## Unit keys

All Units:
* D = Attack
* V = Stop
* G = Hold
* T = Patrol
* H = Move
* Space = useful ability
* E/C = any ability requiring precision

All workers:
* Space = Basic building
* E = Advanced building
* F = Return cargo
* Y = Gather

All CC/Hatch/Nexi:
* Space = worker
* E = important command MULE/Queen/Chrono
* C = scan and recall

Transport/Bunker
* E = unload all
* C = Load

Terran:
* Space/R = "transformers'" keys
* Space/F = cloak/decloak
* 4 = select worker key
* 5 = halt key
* 4 = land key
* 5 = lift key
* C = ignite after burner (coop)
* R = Salvage
* R = Load CC/Planetary Fortress
* F = unload all
* C = Reactor
* E = Techlab

Protoss:
* Space = blink guardian shield feedback
* Space/F = oracle pulsar beam
* Space/R = warp prism (phase mode)
* E = evolve building to warp
* M = evolve back building to non-warp (intentionally out of compact keys)

Zerg:
* R/4 = burrow/unburrow
* C = creep tumor
* F = morph/evolve
* E = speed key (for research affecting speed)

## Building Consistency

Building consistency between race, allows better off-race and random play.
Hereafter are the principles

Basic buildings:
* E = Command center / Nexus / Hatchery
* F = Refinery / Assimilator / Extractor
* D = Supply Depot / Pylon
* 4 = Engineering Bay / Forge / Evolution Chamber
* Space = Turret / Photo Cannon / Spore Crawler (RapidFire air defence)
* C = Barracks / Gateway / Spine Crawler

Advanced buildings:
* D = Factory / Robo
* R = Starport / Stargate / Spire
* G = Fusion core / Fleet Beacon / Ultralisk Cavern
* E = Armory ~~(same as Engineering Bay / Forge / Evolution Chamber)~~

### Bridge method

Bridging method is used to try to facilitate learning.
Research will tend to have the same key as unit production key,
so as the building enabling the production of this unit.

Feel free to report inconsistencies in the GitHub project's issues

## Unit Production

Some mnemonics:
* D for basic units in the command card
  * zergling
  * marine, hellion, viking
  * zealot, immortal, phoenix
* R for support unit
  * roach
  * marauder, hellbat, liberator
  * stalker, void ray
* F for sneak
  * infestor
  * reaper, widow mine, medivac
  * adept, warp prism, oracle
* V and G for advanced and ultimate units (exception = zerg)
* Space for high profile casters (high templar, ghost, raven), and detectors

### Zerg larvae

Hatchery/Lair/Hive "Select larva" has many alternates to prevent waste of time producing new units en masse:
* Drone (Space)
* Zergling (D)
* Roach (R)
* Hydralisk (C)
* Corruptor (T)
* Ultralisk (G)

In this way all keys of the dense cards are useful for hatcheries, lairs and hives.
Alls units are covered apart from:
* Overlord (E, same key as Queen, say E is Zerg mineral only macro units key)
* Viper (4, same key as research burrow)
* Infestor (F, same key as Lair/Hive)
* Mutalisk (V, same key as Pneumatized Carapace, exception to speed research unique key)
* Swarm Host (Y, very out of compact command card: feel free to change if you are Swarm Hosts heavy in your BOs)

For those units, they are either spellcaster or situational, or you simply don't want to accidentally make too many of them.
(i.e. Mutalisk in current meta, just one round to harass and force reaction from opponent is enough,
dumping accidentally all larvae on overlords could easily turn into a disaster)

## Rapid Fire and Precision keys

### RapidFire keys

There are now far more Rapid Fire Hotkeys than in the first TheCore Lite release:
Space, R, T, Y, D, F, G, H.
All warp-inable units are bound to Rapid Fire keys.
If you don't know what rapid fire keys are, please check out JaKaTaK's videos on Youtube.
You can keep those keys pressed and just move point on the target,
as RapidFire key hold will select target with no click needed.
After the target being selected the ability will be called again and you just have to point at the next target.
This property is also known as "smart cast"

source: [JaKaTaK's Rapid Fire Hotkeys thread](http://www.teamliquid.net/forum/sc2-strategy/446530-rapid-fire-hotkey-trick) on TeamLiquid.net

#### RapidFire Static Defence

All workers have Space for "Basic building".
Air defence strutures are mapped on this key
To build static air defence:
* select workers
* go to area
* hold Space and move the pointer to order defence build, it will chain:
  * select basic building
  * select defence building
  * target location where to build

### Precision keys

"E" and "C" keep on being non Rapid Fire, because they are precision keys.
They are used for precision spells/ability,
and have been chosen because of ease of access.
You can keep those keys pressed and just click on the target.
After the click, the ability will be called again and you just have to click on the next target.

**Note:** like legacy TheCore Lite, some spells have 2 alternates; one on "rapid fire" key, the other on "precision" key

#### After precision key usage

Holding precision key for multiple cast, you will end up to have to cancel targeting.
For this there are several option:
* cancel key "Escape"
* rightclick will cancel targeting
* V is now an alias for CancelTargeting
* select another group
* select|box other unit(s)

The 2 last save you APMs if some others unit/building need action

#### High Templar group example

(experimental, fun fact)

Case study assuming HTs in a group following some ranged units not to run into enemies.

Important to know:
* after feedback/psistorm cast, HT will give up follow, think about make the entire group re-follow
* in case HTs were too far to cast and enemy moved, you still can cancel the cast:
  * issuing a move command on the entire group with double RightClicks (1st one will cancel targeting if needed)
  * using V will cancel the target and make stop all selected units
* caster split
  * cast area of effect spells far away on the minimap (eventually rapid fire...)
  * hold V to cancel targeting and stop the casters, it will cancels the spells that were not casted
  * **Note:** V cancel targeting only works with pointer on map

----------------------------------------------------------------------------------------------------------------------

TheCore Lite User Interface keys
================================

Compared to legacy TheCore Lite, many changes occured in User Interface keys.

## Function keys
* F1 IdleWorker
* F2 Toggle minimap colors (no more Select all army on this key - see Tab key)
* Ctrl+F1 Select all Idle Workers
* Shift+F1 Toggle minimap terrain
* Shift+F2 Team Ressources
* Alt+F1 PushToTalk (to free Alt+Shift)
* Alt+F2 Show FPS
* Shift+F7 Toggle sound (moved to prevent mistyping)
* Shift+F8 Toggle music (could be mapped on Shift+F5 to free space)

## Other tips

### Select All Army on Tab key
* Ctl+Tab : alternate for "select all army"
* Ctl+Shift+Tab : alternate for "select all army"

This makes sense considering
[synergy with mouse clicking and group creation](https://github.com/bobo38/TheCoreLite/blob/master/README.md#groups-and-mouse-synergies-with-ctrl-and-ctrlshift)

### Browsing subgroups
* Tab and Shift+Tab are used
* Back/Forward Mouse Button added to browse between subgroups

### Ping allies !
* Alert jump accessible with Shift+Grave
* QuickPing now mapped on Alt+RightClick

### Fight against invisible
* Alt+T : Rotate camera Left
* Alt+G : Rotate camera Right

Immobile invisible units can't be seen with static camera.
Camera rotation allows to spot invisible static units.
Alternate Alt+T and Alt+G to rotate the camera and send detection at the right place.
Alt+RightClick pings the invisible unit location to allies.

### More Town cameras
* B remains toggles base camera
* New alternates
  * Shift+Alt+E

### AI keys now supported
* direct attack on Shift+Alt+R
* direct scout on Shift+Alt+T
* direct detect on Shift+Alt+F
* direct expand on Shift+Alt+C
* delete on Shift+Alt+V
* clearall on Shift+Alt+G
* build style on Shift+Alt+4
* open AI communication on Shift+Alt+5

## Moved out of the dense keycard and Function keys
* Period: Warp (to encourage production group)
* Numpad0: Quick save (no usage in Multiplayer)
* Insert: CameraFollow (confusing feature)
* Apostrophe: Minimap ping (preferred usage of QuickPing Alt+RClick)
* BackSlash: All life bars (better use show "damaged" units)
* Bracket Open: Allies life bars (better use show "damaged" units)
* Bracket Close: Player life bars (better use show "damaged" units)
* 9: set egg rally point (prefer right click)
* 0: set rally point (prefer right click)

----------------------------------------------------------------------------------------------------------------------

TheCore Lite Macro groups
=========================

## History

Legacy TheCore Lite comes with suggestions of control groups.
Q is intended for production facilities or inject queens.
W is intended for CC Nexus Hatcheries + Tech.

Find the original suggested control group suggestion [here](https://docs.google.com/spreadsheets/d/1v1gTY9suNstl6KoYQ0zIA8_dIBAJ9COmdtbQ1AEuxV4/edit?pref=2&pli=1#gid=56)

## Nexus/CC/Hatch group = W

Group content:
* All Nexus/CC/Hatch
* Terran and Protoss should add research facilities to this group

Tip for additional expansion and related alternates:
* Center base at camera creation with:
  * Alt+Shift
  * Alt+CapsLock
  * Alt+Tab
  * Alt+`
  * Control+V
* Add to Nexus/CC/Hatch with alternates
  * Alt+D (legacy could be removed)
  * Alt+Q

## Production group (or inject queens) = Q

Group content:
* Terran & Protoss: All army production facilities
* Zerg: inject queens
* Zerg should add research facilities to this group

Tips for rally point | warp-in pylon:
* Shift+Q has the same effect than pressing Q
* Shift+Q+W mechanics
  * Shift+Q selects this group
  * Shift+W recalls camera (rally point)

Related alternates:
* none, the alternate for control camera was removed

Race specific:
* Related to warp-in
  * Keep shift pressed, while holding unit key (queued rapid-fire warp-in)
  * Shift+3 could be used for secondary warp-in zone
* Related to egg inject
  * W camera would be main hive
  * Shift+Q+W helps getting Shift already pressed for queued commands
  * please read dedicated usecase "Telegraph inject" and "TheCore inject"

## Utility group = 1

Group content:
* wall supply depots
* creep queens
* please report any other usage

Alternates for "recall utility group":
* Shift+V

Usages:
* Creep queen with shift
  * Shift+V+V = select + jump to creep queen (same raw as C for fast spawn creep tumor)
  * Shift+C + clicks = queued drop creep tumors
* wall supply depots burrow
  * Shift+V+Space: select wall supply depots and burrow

## Trash group key = Grave

Grave is an alternate for ControlGroupAssignAndSteal6,
to be used for creating with steal a CapsLock group from current selection.
With this direct access key you can remove units from any group, and get a temporary control group for microing those

## Group display

The 2 "macro" groups are positioned in the center to split the remaining groups by 4 keys.
This facilitates the visual representation of existing groups.
The 10 groups are displayed in this order (| figures the separation):
```
123|QW|CapsLockASZX
```

**Note:** the icon representing the group seems to be the best selectable unit at group creation.
If you wanted to update the icon, select the group and recreate it.

----------------------------------------------------------------------------------------------------------------------

TheCore Lite Group/Cameras modifiers
====================================

## History

Compared to legacy TheCore Lite:
* all group keys are similar
* modifier have been changed

LoTV introduced steal behavior, for Archon mode.
"Steal" enables to remove the selection from any other groups,
including Archon partner or your own groups.
TheCore team concluded that this property worths using it by default.
JaKaTaK explains pros and cons in this video: [To steal or not to steal](https://www.youtube.com/watch?v=ayngEqIaWmM)

For TheCore Lite, here are the modifiers:
* AppendSteal = Ctrl
* CreateSteal = Ctrl+Shift
* Create non-steal = Shift+Alt
* Append non-steal = Control+Alt

## Groups and mouse synergies with Ctrl and Ctrl+Shift

Those behaviors are similar if Alt is pressed simultaneously:
* Ctrl+
  * one click on the map, selects all visible units similar to target
  * one click on the board, keeps selected only units similar to target
* Ctrl+Shift+
  * one click on the map, adds all visible units similar to target in selection
  * one click on the board, removes all units similar to target in selection

In case you want to split a group,
just box some units then appendsteal them to another group with Ctl+click+#groupnumber.

In case you want to remove a unit type from a group
* Ctl+click a unit+#groupnumber, you probably want all units to be a target group anyway
* Ctl+Shift+click a unit+#groupnumber, deselected units won't have any group :(

Shift+Alt would be recommended if you want to remove some units from control groups.
Just recreate group with Shift+Alt after shift clicking the units supposed to stay at their place
(or execute the last command - read next section).

Some examples with "Select All Army":
* After Ctl+Tab
  * Ctl+click will select only all units of the clicked type
  * Ctl+#group key will append/steal the selection
* After Ctl+Shift+Tab
  * Ctl+Shift+click will remove any unit of the clicked type
  * Ctrl+Shift+#group key will create/steal a group with this selection
  * alternatively Shift+Alt+#group key will create group/non-steal the selection

### Additional group for easy caster selection through Ctl+Alt

You may want to have units in both a main army group and a caster group.
It is the case of the Stalker group in [JaKaTaK's video on Protoss control groups](https://www.youtube.com/watch?v=Hu7sLfLpkaM&index=10&list=PLiejbQlQAdGlM1wWWxMGZsBAFCrIRjGJn).

* Select the group where the casters are
* Ctl(+Alt)+LeftClick a caster in the board (select only all units of a given type)
* Ctl+Alt+group# to append in a group without stealing from the main army
  * Use Shift+Alt+group# could be use to create/overwrite, but chains not as well

There is a documented ["combined production group"](https://terrancraft.com/2016/02/24/terran-control-group-set-up/):
it uses the recommended production group,
with easy recallable for factory/robo and air.
Z and X would be recommended for this usage, as they are easier to combine with Control+Alt.

## Easier cloning through Shift+Alt

Shift+Alt+LeftClick acts as Shift+LeftClick when deselecting a unit from the selection.
Shift+Alt+RightClick is an alias for Smart Command, it **inhibits the queuing**.
As a consequence Shift+Alt could be hold during a typical cloning routine.
More info at the following URLs.

Shift+Alt+#groupkey is used for create/non-steal group.
It could help in creating groups after unit deselection.
Please refer to JaKaTaK video for more details.

sources:
* [TeamLiquid's page about "Cloning"](http://wiki.teamliquid.net/starcraft2/Cloning)
* [JaKaTaK's "How to clone - manual cloning" video](https://www.youtube.com/watch?v=S4Q9ghZbqpA&list=PLiejbQlQAdGnuLyxXEC7fnLIy-hdD7J-8&index=7)
* [JaKaTaK's "How to clone - control group cloning" video](https://www.youtube.com/watch?v=1cozEzPaxnw&list=PLiejbQlQAdGnuLyxXEC7fnLIy-hdD7J-8&index=11)

**Warning:**
Alt+Shift is an alternate for center on selection.
It could mess up your cloning, if you don't press exactly Shift+Alt.
You could think about unbinding it, as there are enough other alternates.

## Shift/Control and camera synergies

### History

TheCore Lite keeps on having Shift+cam# for cam# recall.
It chains good with queuing,
allows sending worker back to work,
easy cam access for multiprong defence

Compared to legacy TheCore Lite:
* camera creation still based on Alt modifier
* camera recall still based on Shift modifier
* "control" cameras were introduced
* Q camera is no longer used, in place 1 is used

### Additional cameras alternates on control

3 "Control" camera alternates:
* Ctl+C = Shift+1
* Ctl+D = Shift+2
* Ctl+E = Shift+3

Camera creation:
* Ctl+V = Alt+1
* Ctl+F = Alt+2
* Ctl+R = Alt+3

Those aliases allow easy save/recall locations.
Same modifier is applied for save and recall.
Using them you have a finger on Ctl:
Ctl+LeftClick on a units selects all visible units of this type.
It is particularly useful for spreading creep.

Still experimental, feel free to adjust to your needs.
Current implementation is for 2 creep cam and easy jump from cam 1 to 2

Related aliases:
* Ctl+Space = rapid fire creep spread
* maybe an alias needed for centering cam on selection while control is pressed

**Note:** control cam could be used for warp gate with a proper alias for

### Other features
* Alt now shows Enemy life bar (useful for quick check for mana bars of stacked ground/air armies)
* Shift+` is used for jump to last alert

### Quick Cam

(not implemented but practically working, kept for hotkey hack documentation)

* ~~Camera 1 creation with Shift~~
* ~~Camera 1 recall with CapsLock~~

~~This cam is updated each time you press Shift.~~
~~You can recall to base and be back at last position if you don't press Shift twice~~
~~Camera 2 and 3 are kept in case you want to use them for harass.~~

~~Note: previous quick cam implementation was removed, kept in readme in case you want to reintroduce it in your local copy~~

----------------------------------------------------------------------------------------------------------------------

Use case scenarios
==================

## Use case: Start Sequence
* hold Space before match begin
  * immediately click CC/Nexus/Hatch at start-up it will launch worker production
  * in case of zerg click again afterwards to reselect hatch and not append eggs to Hatch group
* from here keep thumb on Alt
* create first base cam
  * Alt+Tab center on CC/Nexus/Hatch
  * Alt+Q: append to CC/Nexus/Hatch group
  * create main base cam:
    * Alt+A: for Terran & Protoss
    * Alt+W: for Zerg (zerg don't need rally point !)
* move pointer on minimap and hold left click, it will make the main screen follow the pointer location on minimap
* rally point cam for terran/protoss
  * move pointer to ramp or expected early rally point
  * Alt+W
* set new expansion cams, for each cam:
  * move pointer on expected cam location
  * Alt+(A|)S|Z|X
* release Alt and left click
  * check mineral level for benchmark

**Note:** during cam creation, your CC/Nexus/Hatch keeps on being selected,
just follow launch next production when ressources available.
For terran and protoss you see the worker production timer.
For zerg, best is to spawn an overlord at 100 minerals after 1st drone.

## Use case: expansions cameras
* Select new base under construction
* Alt+CapsLock|`|Tab: center view on base
* Alt+[camera\_key]: make view on associated key
* Alt+D|Q: Append expansion to Nexus/CC/Hatch group
  * Alt+D is legacy and could be removed for v2.3

Recommended:
* select new base under construction
* Alt+Q+Tab+[camera\_key]

## Use case: send worker back to resource gathering after queued commands
* press shift to queue all necessary commands
* Shift+[camera\_key]: jump to base
* Shift+RightClick on mineral or gaz; last action of the queue is to go back to work

## Use case: army production + rally point (optional warp-in pylon)
* Hold Shift
* Shift+Q: select production facilities
* Shift+W: jump to rally point (declared with Alt+W)
* inspect rallied army
* optional redeclaration of the rally point (RightClick, in case of new integrated facility)
* browse subgroup and launch production
* select rallied army and add to control groups

## Use case: warp-in pylon

#### with Shift camera
* Hold shift
* Shift+Q: select production facilities (WarpGate have higher selection priority)
* Shift+3: jump to warp-in camera (S as a suggestion with Z for the regular rally point)
* Shift+key for warping-in units (queued rapid fire warp-in)

#### Other tips
* Ctl+click: on a unit, select all units for this type
* right click for rally

## Use case: TheCore Lite inject initiate

* Shift+Q = select inject queens + tech
* Shift+W = jump to main hatch (first hatch)
* Shift+Space = inject
* center mouse
* keep Shift hold (to queue target)

## Use case: Telegraph inject (Backspace family)

The "Telegraph" inject is an implementation of the [Backspace inject](http://wiki.teamliquid.net/starcraft2/Spawn_Larva_(Legacy_of_the_Void)#Backspace_Method).
It relies on:
* no mouse click
* 2 neighbour keys, comfortably pressable
* holding left Shift during the whole inject phase
* to queue command

Method:
* Start with a "TheCore Lite inject initiate"
* Then keep Shift pressed and move thumb on Alt
* Shift+Alt+E used to cycle base
* if queen is there, with enough energy, left click
  * Shift+Alt+D used to TargetChoose, like LeftClick (Rapid Fire key)

**Note:** In case of wandering queen, release shift and press V

## Use case: TheCore inject

The [TheCore inject](http://wiki.teamliquid.net/starcraft2/Spawn_Larva_(Legacy_of_the_Void)#The_Core_Method)
benefits as well of TheCore Lite inject initiate.

* TheCore Lite inject initiate
  * Shift+Q = select inject queens + tech
  * Shift+W = jump to main hatch (first hatch)
  * Shift+Space = inject
  * center mouse
* Shift+A|S|Z|X+click = base camera + inject if needed

Suggested camera locations:
* W main
* A 2nd
* S 3rd
* Z 4th
* X 5th

## Use case: Camera creep spread

This step benefits from holding Ctl.
Ctl+click acts as select all units of the same kind.
Control click on tumor to select all that appear on the screen.
Creep tumor spread has a RapidFire alias (Space).

This section is outdated, control camera hotkeys are practically not that convenient to use

* ~~ initiate ~~
  * ~~ Ctl+D = jump to creep camera 1 (initiate) ~~
* ~~ select all creep tumors with Ctl+click ~~
* ~~ creep spread ~~
  * ~~ hold (Ctl)+C then clicks = spread creep tumor (precision key) ~~
  * ~~ (Ctl)+Space = spread creep tumor (rapid fire) ~~
* ~~ optionally centering ~~
  * ~~ click = select a new creep tumor ~~
  * ~~ Ctl+V = center view on selection ~~
* ~~ save and restart from "select all creep tumors" ~~
  * ~~ Ctl+R+F, save 1 jump to 2 ~~
  * ~~ Ctl+E, get fingers back on rest keys ~~

**Note:** keep in mind that selecting another group cancels the action

## Use case: hatching eggs

Easy hatch eggs:
* W selects hatcheries
* select larvae and launch production: Space, D, R, C, T, G
* some units need select larvae with another key
  * [read more details here](https://github.com/bobo38/TheCoreLite#zerg-larvae)

Overlord map control "W+Space+E+Right click on minimap":
* W select hatchery
* Space select larvae
* E spawn overlord
* Right click on minimap, sets rally point.

## Use case: zerg macro routine

* Eggs pop, you have 2.746s for your queens to reach +25 energy
* Hatch check
  * W: hatch group
  * morph larvaes depending on needs (drone or army)
  * add eggs to control groups and give them rally points
* Inject routine
  * use TheCore Lite Inject initiate
  * then "TheCore inject" or "Telegraph inject"
* Tech check
  * You had time to check upgrades as they were selected with inject queens
  * browse subgroup + add new research
* Creep queens (see "utility group section")
* Creep cameras (control cameras) holding control
* Use natural larvae to make overlord
  * morph 1 overlord/mining hatch/egg cycle
  * rally overlords individually to strategic locations

Extra:
* sync Queen birth and Hatch spawn with the macro cycle
* sync building spawn with next eggs' pop (build order)

sources:
* [JaKaTaK's "Egg Hotkey Drill" video](https://www.youtube.com/watch?v=GWgwuce9q6o&list=PLiejbQlQAdGl0uqlZUauzrxwcM5fquSPh&index=6)
* [JaKaTaK's "Rapid Fire Creep Spread" video](https://www.youtube.com/watch?v=av2kaBI-gKg&index=11&list=PLiejbQlQAdGl0uqlZUauzrxwcM5fquSPh)
* [Zerg Cycle Revisited - LoTV](http://www.teamliquid.net/forum/sc2-strategy/524948-zerg-cycle-revisited-lotv) (Team Liquid forum thread)
* [\[G\] The Cycle method for Zerg macro](http://www.teamliquid.net/forum/sc2-strategy/274298-the-cycle-method-for-zerg-macro) (Team Liquid forum thread)
* [larva usage factor, or why you might be macroing wrong](https://6pool.blogspot.de/2017/12/larva-usage-factor-or-why-you-might-be.html) (blog)

## Use case: Easy MULE/Chronoboost

Protoss and Terran have also some macro optimization with TheCore Lite \o/

#### Variant 1
* W: select CC/Nexus
* E: key for MULE/Chronoboost, precision key, no risk of rapid fire
* Shift+[camera\_key]: jump to base
* hold shift + click on wanted locations

#### Variant 2
* Shift+[camera\_key]: jump to base
* W: select CC/Nexus
* hold E: key for MULE/Chronoboost, precision key
* left click on wanted locations

#### How to end

After usage of the variant 1:
* releasing shift will cancel targeting on queued command
  * only works if one LeftClick has been performed

Otherwise please read "After precision key usage" section.

----------------------------------------------------------------------------------------------------------------------

Further optimizations
=====================

TheCore Lite is a consistent set of commands which could see further optimization.
Without changing the [Commands] section you can easily play around with [Hotkeys] section

## The Control key placement

The biggest weakness is Control key placement.
Here are 2 ways of dealing with Control key:
* tilt keyboard clockwise by 10-20° to get super comfortable with fingers on Shift/Q/W/D/Space
  * Control will be 1 key below a comfortable key
* remap CapsLock as Control key at Operating System level
  * Control will be comfortable with straight keyboard

Changes implemented at my local copy:
* use mouse only for browsing subgroup Back/ForwardMouseButton, to free Tab
* change Select All Army to keybind to allow group modifiers with Tab (by me Shift+Tab)
* use Tab as CapsLock group
* CapsLock is now free to be used as Control modifier with external software. Note: you may not be able to use Alt in conjunction with Tab. Consequently, I only have the Ctrl and Shift+Ctrl functions for this control group.

## Other possible tweaks

Device inputs:
* use wheel up/down as Back/ForwardMouseButton with external mouse software (work for 3-buttons mouse)
* map middleButton to othe mouse button with external mouse software (CameraPush)
* increase keyboard key repeat rate (more actions through key repeat)
* decrease time to start keyboard key repeat (less delay for repeat)

User Interface:
* Graphics: [Hybrid settings](http://www.teamliquid.net/forum/starcraft-2/498454-hybrid-settings-30-lotv-edition#1) are optimizing game info versus FPS tax
* Gameplay: check all boxes apart enable simple command card
  * "enable select enemy unit" is controversial as it may cause some issues
* Sound: uncheck "Response Sounds" and "Ambiant Sounds"

----------------------------------------------------------------------------------------------------------------------

Changelog for the code
======================

Compared to upstream project:
* TheCoreRemapper.py supporting other seeds than pure TheCore
  * support for Left/Right conversion was removed
* New "seed" checks:
  * check for unbound commands, known from conflicts
  * check to prevent conflicts between Hotkeys (i.e. directly access such as groups, base camera key) and Commands
  * regression check against stable version for Multiplayer
  * check key consistency over CommandRoot
* New "quality" checks:
  * check for commands out of known conflicts (warning only in case of inherit/same)
* Debug mode
  * optional generation
  * optional seed selection (you could run the script for the seeds you want)
  * optional quality checks (otherwise just run "seed" checks)
  * optional hint through a "verbose" and "verydetail" options (including the remapHint function)
  * optional IgnoredContext (such as "WoL Campaign" or "Coop") to filter conflicts and keys
* Some .ini file fixed to prevent wrong positives

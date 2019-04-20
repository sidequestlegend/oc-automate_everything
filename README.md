# oc-automate_everything
Minecraft opencomputers project. Aimed for automating everything in a system.<br>
Starting from two robots, then they expand themselves into an unlimited resource generator!

## Why two robots?
Because a robot cannot eject a floppy disk from itself :)

## Progress
- Robot navigation system [WIP]
- Crafting system [Currently WIP]
- Smelting system [Not yet]
- Inventory system [WIP]
- Logistic system [Not yet]
- Mining system [Not yet]
- Logging system [Not yet]
- Replication system [Not yet]
- Storage system [Not yet]
- Player interface [Not yet]
- Extra: Infrastructure building system [Not yet]

## How to try?
External: Retrieve this repository's content.<br>
Ingame: Put a `Creatix` on the ground and insert an empty floppy disk into the robot's slot.<br>
External: Copy all of the 'floppy' folder content from the repository into the floppy disk folder inside your minecraft save world.<br>
Ingame: You pull the empty floppy disk and then put it back again.<br>
Ingame: You need to be in the floppy's root directory before executing any of the programs, e.g: `/mnt/875/`

## What can I try?
You can try running `craftingmanager` and run these lines of code slowly:
```
help
    Not a code: You scroll down by pressing the `space` key until it finishes printing.
load crafting
load raw
    Not a code: You put a cobblestone stairs' recipe into the robot's crafting grid
    Not a code: Empty slot 8
select 8
analyze shaped true
show slot
keep
save crafting
exit
```

## Suggestions Welcome
If you want to help me improve, let me know by opening an issue :)

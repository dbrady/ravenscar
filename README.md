# Ravenscar World Notes and Commands

# Ops Bunkers

There are special "ops bunkers" hidden in the bowels of Ravenscar. *Op Bunker
Prime* is located at the bedrock below 0,0. To reach it, manually teleport
yourself to <1, 1, 1>. I am working on creating some ops-only teleports to make
this easier on us but for now you can always teleport yourself to the origin to
reach Ops Bunker Prime.

Ops Bunkers also contain command-block workbenches. These are tinkering benches;
feel free to overwrite any scripts you find contained in them. If you create a
command block script you want to keep, copy the command block with
cmd-middle-click, which will give you a copy of the command block with the
script saved inside it.)

All Ops Bunkers are completely enclosed in bedrock to prevent accidental
discovery, and for lore purposes all but Prime are placed below villages where
players are forbidden to mine.

## Ops Bunker Prime

Located at the world origin, this is intended largely to be a teleport hub for
getting around.

`/teleport <nick> 1 1 1 0`

<font color="red">**IMPORTANT**: Do **NOT** teleport to 0 0 0, or you will
fall out of the world!</font>

## Ops Bunker Alpha

This ops bunker is located at the bedrock below Rusty's Mystical Magical Grand
Trade Emporium ("Rusty's Shop") in Ravenscar. This bunker contains command
blocks for Ravenscar town, Rusty's Shop, and the world at large.

This bunker is important because it is directly below the spawn point, which
means its chunk is always kept loaded. Command blocks that need to run all the
time should be placed here; command blocks placed outside the spawn chunk risk
being unloaded.

The easiest way to reach it is to go through the teleport hub at 1 1 1 0. Turn
left and right-click the Ops Bunker Alpha warp sign. Alternately you can step
outside Rusty's Shop, enter `/gamemode 3` and sink down through the ground to
the bedrock.

# Getting A Command Block

Command blocks are enabled on Ravenscar, but cannot be obtained naturally. To
get one:

* `/give <nick> command_block`
* Middle-click on an existing command block (Cmd-middle-click if you want to
  copy it with its scripts intact.)
* Check in the chests in the ops hubs; sometimes I store my extras in there.


# How To Use These Programs In A Command Block

Place a command block, and then place another block adjacent to it. Put a button
on the neighboring block and you're ready to go. Right click the command block,
paste in the command, click Done, and then hit the button to activate the
command.

The OS clipboard works between your browser and the command block, so it's
pretty simple.

# Testing Dangerous Commands

In a word: Don't do it in Ravenscar. Use your own private world, please. There
is no "undo" and damage to Ravenscar can only be removed by rolling back to a
backup.

# What's In Here
* `/bin` scripts and programs for manipulating and creating data
* `/gives` scripts and commands to give custom items (warp signs, etc)
* `/summons` json files for summoning specific entities

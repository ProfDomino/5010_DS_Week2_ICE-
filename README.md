ICE - week 2:
=============

Accept this assignment on Github classroom.


# Part 1: adding inheritence to Agent

1. Clone down the new repo

1. Copy your Agent_og.py into this new directory

1. Re-name that copy of Agent_og to ParentAgent (optional: rename the file too)


## 1A: Making a DiverseAgent

1. Now create a new file called `diverse.py`.  Create a new class called `DiverseAgent` that is a child of ParentAgent.

1. In the `__init__` of DiverseAgent, call the `__init__` of ParentAgent using `super()`.

1. In DiverseAgent - After calling the parent's `__init__`, reset threshold attribute to be a random number between (0.1 and 0.3)
	* This will mean that DiverseAgents all will have a very low requirement for people in their own group

## 1B: Making a ConformingAgent

1. Now create a new file called `conform.py`.  Create a new class called `ConformingAgent` that is a child of ParentAgent.

1. Call the parent class’s `__init__()` just as you did with DiverseAgent

1. In ConformingAgent - after calling the __init__ of the ParentAgent, set the threshold to be a random number between (0.5 and 0.7)
	* This will mean that DiverseAgents all will have a very low requirement for people in their own group


# Part 2: Making use of our new Agents

1. Copy in `city_og.py` from Homework 1

1. Wherever you create X Agent objects, change them to be DiverseAgents
	* Note - their group should still be set to X

1. Wherever you create O Agent objects, change them to be ConformingAgents
	* Note - their group should still be set to O

1. Run a 5x5 simulation for 10 rounds just to confirm it all works

# Part 3. More practice with git

1. Run the command `git status` in your terminal.  
	* Note - make sure you're in the correct directory in your terminal!
	* this step is never necessary, it just can be a visual into what Git is tracking and where it sees changes.

1. Stage all of these files for commit by running `git add <filename>`
	* You'll need to run this command once for each file that's been changed in this directory 

1. Run the command `git status` command again - your files might have changed color!

1. Commit those changes by running `git commit -m "Week 2 ICE"`.  

1. Run the command `git status` in your terminal again.  It should say something like "nothing to commit, working tree clean"

1. Push those changes up to remote by running `git push origin main`

1. Confirm that your changes did indeed make it up to the online version of your code.

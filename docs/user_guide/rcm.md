# RCM

RCM (short for ReCovery Mode) is a mode for the Switch that allows Nintendo to send the Switch commands to do various things. People found out that on unpatched Switches, you could send a payload, and then quickly copy it into the memory buffer behind the stack, overflowing the memory buffer into the stack, meaning you smash the stack and get full access to everything on the system. We use it here to launch GalacticNX.


----

### emuNAND CFW

!!!tip "What's needed for emuNAND"
	- A microSD card that's 64GB or larger

	#### Pros of using emuNAND over sysNAND CFW:
	
	- Using homebrew applications such as save editors, or cheating in games offline without "dirtying" or affecting sysNAND, allowing sysNAND to be used online without ban risk.
	- Allowing users on patched Switches using Caffeine to update their emuNAND to latest and use it online, keeping sysNAND at a lower vulnerable version.
	- Galactic only supports emuNAND/emuMMC on unpatched units at this time.

&nbsp;

#### [Continue to Entering RCM <i class="fa fa-arrow-circle-right fa-lg"></i>](emummc/entering_rcm.md)
-----

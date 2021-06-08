# NR6 HAL Manual

## Introduction:
NR6 HAL is a modernization and enhancement of the "HETMAN Artificial Leader" modification for ARMA 3, originally created by Rydygier. NinjaRider600 then created a newer version of the mod with several marked improvements over the original. Some of this enhancements include converting the script-based function of the original mod to more intuitive standard ARMA system modules, and refactoring the objectives system to eliminate the four objective limit. NinjaRider600 also packages additional modules with his version of the mod, and this guide will explore them in detail below.

## Basic HAL Modules:
*Modules required for a simple HAL setup.*

### **HAL Core**
The HAL Core module is the center of any mission with any amount of HAL Commanders. Only one is required per mission, and all HAL Commanders must be synced to it in order to function.

#### Settings:
The HAL Core module has only one setting, `Startup Delay`, which sets (in seconds) the delay which after the mission begins that HAL Commanders begin to give orders.

---

### **HAL General Settings**
This module controls additional mission-wide settings that apply equally to all HAL Commanders in a mission. In order to function properly, it must be synced to the HAL Core Module.

#### Settings:
- `Enable Cargo Recon` (Defaults to `Enabled`) - *"Recon orders will use provided lifts."* - Controls whether squads assigned to recon objectives will use commander provided lifts as opposed to just walking.
- `Synchronized/Timed Attacks` (Defaults to `Disabled`) - *"Attacks will be timed and synchronized among squads attacking the same target."* - Allows greater strategic cohesion between squads when enabled, allowing them to plan synchronized attacks.
- `Radio Comms` (Defaults to `100`) - *"Chance for a communication between AI and commander to be visible and audible"* - Determines the percent (0%-100%) chance that messages relayed from a squad, such as the "We're pinned down here!" messages to be visible in side chat and played for players as a radio message.

# Zbot

Pokémon Go Discord bot with the ability to read raid screenshots and more

Named after Porygon-Z, Zbot is a Python 3.5+ code for a Discord bot to help
organise small Pokémon Go communities. Keep track of:
* Raids
  * Via gym screenshot
  * Via text command
* Raid attendance
  * Express interest in a raid via Discord reactions
  * Suggest a meet time via text command
* Research rewards

Small details:
* Raid cool-down timers for each gym
* "Say what you mean" text command system
* Typo/spelling tolerance on Pokéstop/Gym locations

__Requrements__

Minimum Python version 3.5 (for `asyncio`)

Modules 
* `discord.py` Rewrite branch https://github.com/Rapptz/discord.py/tree/rewrite
* `numpy`
* `pyxDamerauLevenshtein`

Optional modules (for image recognition)
* `pytesseract` (requires tesseract installation)
* `opencv`

Tested on x86_64 Linux/MacOS. ARM64 (Aarch64) Linux.

__Installation__

`git clone https://github.com/PoGoZbot/Zbot`

`pip install -U --user -r requirements.txt`

__Configuration__

Zbot needs to be configured with
* Gyms and Pokéstop names (optionally locations and images)
* Discord bot token
* IDs for the Discord channels for it to use

# MultiAgent-Systems-StarCraft2-Spring-AIResearch

Contains:
- Siraj Raval's code for SC2 demos
- New modified code based on the pysc2 API to work with Raw Interface

Modifications:
- Added observation() method in s2env_modified.py to get observation
- Added isAvailable() method in s2env_modified.py to check if specific action is available for current state
- Added transform_raw() method in s2env_modified.py to setup raw actions
- Added cmd_raw() in actions_modified.py to setup raw_commands, including setting up in ArgumentTypes and Functions.
- Working on generalizing the performance of raw actions and retrieval of raw observations.

# Player Lookup
This page contains info about `/app/player/<player_name>`.

This page does not require being logged in.

## From where player lookup gets its data?
Player Lookup querries data from two sources.
- Mojang
- Pequla's datalink

Data obtained from mojang is
- UUID
- Player skin

Data obtained from Pequla's datalink is
- Discord account asociated with UUID
- Account history

## CCI
CCI stands for **quick copy info**.

Here you can find everything about a player in a standardised format
```txt
# <minecraft name> - <discord name>
(datalink id)
<uuid> - <discord id>
===========
AdminTools CCI
```

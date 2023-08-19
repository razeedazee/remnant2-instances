
Your saves come in two parts.

`profile.sav` - This contains the information for you characters like their progress and inventory for up to 5 characters

Each character corresponds to a save file using a number and starting from 0.

`save_0.sav`
`save_1.sav`
`save_2.sav`
`save_3.sav`
`save_4.sav`

These save file contain your world progress info. Importantly, they are also where quest items are stored.

This allows us to hot swap these saves with our profile by loading a save file that corresponds to the character number we want hot swapped.

This means I you don't need a host to do these things as some quick examples.-

- Open Hands for scrap
- Load at a checkpoint before Tal'Ratha
- Load at Nightweaver web with all key items
- Load at any location or checkpoint with a unique world state for events, items or boss kills.

## How to use these

Each instance will have 5 identical copies of the instance for each potential character.

1: Backup up your saves. They are located here for Steam.

```
C:\Users\%USERNAME%\Saved Games\Remnant2\Steam\<STEAMID>
```

2: Delete the save file associated with your character.

3: Hot swap in the instance you want with the corresponding save file

4: Load the game and play the instance.

5: When done exit the game

6: Restore you old save file, NOT your profile.sav.

You will now have an updated profile and in you old world.
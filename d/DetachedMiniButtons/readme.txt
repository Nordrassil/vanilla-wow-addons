This mod attempts to 'detach' all your minimap buttons, allowing you to place them anywhere on your screen. Positions are saved per server/character and restored next login.

This is the first version of this mod, I am sure not all kinks are worked out. I have tested it only with the mods I have, so please let me know which mods create buttons that I cannot detach so I can load them and see what-is-what.

Not all minimap buttons are detected at start up (such as FuBar plugin mods, which has its own moving anyway). A slash command is provided so you can rescan for buttons: /dmbs.  This will also reposition any buttons it failed to find at startup.

Special thanks to AnduinLothar without whose code and ideas in Mobile Minimap Buttons I would not have thought of this.

This mod uses SeaHooks, which is included.

Slash Commands:
/dmbs [help] : show help
/dmbs scan   : look for new buttons.
/dmbs nodock : buttons will NOT try to dock to Minimap when close to it.
/dmbs dock   : buttons will try to dock to Minimap when close to it. This is default.
/dmbs lock   : buttons will not be moveable
/dmbs unlock : buttons will be moveable
/dmbs cfg    : show dock/lock settings.
/dmbs reset  : reset all buttons back to initial positions.
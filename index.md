title: Burning Oasis
---
## Burning Oasis Conan Exiles Setup Guide

So, you want to join us in the inhospitaple desert? Along with a copy of the game, you'll need the following:

* Invite to the server
* Password to the server
* Mods installed and activated

Optionally (though highly recommended), you can change your client's network settings to load the game and bases faster.

### Mods

* [LitMan Loot Legendary Chests](https://steamcommunity.com/sharedfiles/filedetails/?id=1367028501)
* [LitMan Level One Fifty Six](https://steamcommunity.com/sharedfiles/filedetails/?id=1138108077)
* [Pickup+](https://steamcommunity.com/sharedfiles/filedetails/?id=864199675)
* [Glass Constructions and more...](https://steamcommunity.com/sharedfiles/filedetails/?id=901911361)
* [Fashionist (1.0 compatible)](https://steamcommunity.com/sharedfiles/filedetails/?id=1159180273)
* [Pythagoras Support Beams](https://steamcommunity.com/sharedfiles/filedetails/?id=1382183303)
* [Savage Steel](https://steamcommunity.com/sharedfiles/filedetails/?id=1367404881)

Once you've **Subscribed** to each mod, start the game and activate them in the same order as above in the mod list.

### Faster Load Times

On your computer, browse to where you've got conan installed, and edit the `common\Conan Exiles\Engine\Config\BaseEngine.ini` file.


> *Note*: To find where Conan's installed, from steam right click on Conan in your library, select properties, goto the Local Files tab, then click the "Browe Local Files..." button.


Once you have `BaseEngine.ini` open, find and edit the `[/Script/Engine.Player]` section and set the values to `100000`:

```
[/Script/Engine.Player]
ConfiguredInternetSpeed=100000      ; Mike: Default is 10000 (in bytes per second)
ConfiguredLanSpeed=100000
```

More info from [this steam post](https://steamcommunity.com/app/440900/discussions/0/133256689833418626/) and [this unreal engine 4 page](https://answers.unrealengine.com/questions/353439/how-can-i-increase-network-bandwidth-limit.html).

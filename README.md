# Naked and Afraid

Welcome to Minecraft Naked and Afraid, a Hardcore SMP experience where you cannot wear armor and can only communicate through proximity chat.

## Description

Naked and Afraid is a YouTube series where Minecraft content creators try to survive until the very end. PvP is disabled, as well as the in-game chat. Players will be unable to tell who else is online unless they're literally right next to one another, making Naked and Afraid both a skills-based and a psychological challenge.

This means that all means of communication—direct or indirect—are disabled. Join & leave messages, advancements, and coordinates are disabled. Totems of undying are also not allowed in this gamemode. Every time a player dies, a universal death cannon sounds, giving confirmation to players that someone has died, although they might not know exactly who.

If a player puts on a piece of armor, they will begin to take damage. This mechanic cements this SMP as notoriously difficult, where every decision matters. Ultra Hardcore (UHC) mechanics are optional, where natural regeneration is disabled and players can only heal via golden apples, suspicious stews, and potions.

## Getting Started

### Dependencies & Enhancements

* Install the latest version of Skript on the SpigotMC website [here](https://www.spigotmc.org/resources/skript.114544/) (note that the latest version often requires the most recent build of Minecraft).
* You must have Java 17 or later installed on your server for Skript to function.
* Install Simple Voice Chat [here](https://modrinth.com/plugin/simple-voice-chat/versions) for both your server and your client (ex. Paper jar goes in the server's ```/plugins``` folder, while Fabric jar goes in your own ```/mods``` folder). All members must install Simple Voice Chat on their client to hear one another.
* Open an additional port on your server. Navigate to ```plugins/voicechat/voicechat-server.properties``` and set the "port" value to that additional port. Restart the server to apply the changes.
* It's recommended to use a Hardcore Hearts texture pack [like this one](https://modrinth.com/resourcepack/hardcore-hearts) to enhance your experience.
* Also consider enabling a whitelist. In ```server.properties```, set "white-list" to "true" and run ```/whitelist on``` in the console. Use ```whitelist add <player>``` to add all server members to the whitelist.

### Installing

* Download the ```naked_and_afraid.sk``` file, and place it in ```plugins/Skript/scripts```.
* Follow the configuration instructions at the top of the file, or customize them to your preference.

### Optional Tablist Configuration

In the original Naked and Afraid series, the tablist is disabled to remove the ability to identify who's still alive. However, since it's difficult to hide or disable the tablist directly, it ended up looking like [this](https://imgur.com/a/6CXRsa6)—the same is true for this plugin. However, if you want to completely obscure the tablist by removing players' faces, follow these instructions:
* In ```server.properties```, set "online-mode" to "false" and install the latest version of [SkinsRestorer](https://modrinth.com/plugin/skinsrestorer) in your ```/plugins``` folder.
* It's strongly recommended to add a [password plugin](https://www.spigotmc.org/resources/authmereloaded.6269/), as it prevents hackers from exploiting a cracked server and other members from logging in as you. 
* If you decide upon this configuration, make sure to do it before any player activity. Doing so later on will erase all players' inventories and progress.
#### Alternative Method
To "remove" the tablist without potentially compromising the server, simply have all members remove the "List Players" keybind by clicking on its adjacent button and hitting escape.

### Finishing Up

* Once you have tested everything and are ready to begin, enable the Hardcore mechanics by running ```/hardcore-enable``` in the console.
* Enjoy!

## Author

Created by [Enzec](https://enzec.net)

## Version History

* 1.3
    * Removed villagers
    * Made changes to the tablist
* 1.2
    * Added commands to enable/disable Hardcore mechanics
* 1.1
    * Disabled totems of undying
    * Elytras, skeleton skulls, and other non-armor items can now be worn without damaging the player
    * Chat-related commands have been disabled
    * Added a startup and shutdown message
* 1.0
    * Initial Release
 
## To Do

* Disable dispensers from dispensing armor (to prevent Curse of Binding traps)
* Create a custom resource pack that includes Hardcore Hearts and a death cannon sound

# Naked and Afraid

Welcome to Minecraft Naked and Afraid, a Hardcore SMP experience where you cannot wear armor and can only communicate through proximity chat.

## Description

Naked and Afraid is a YouTube series where Minecraft content creators try to survive until the very end. PvP is disabled, as well as the in-game chat. Players will be unable to tell who else is online unless they're literally right next to one another, making Naked and Afraid both a skills-based and a psychological challenge.

This means that all means of communication—direct or indirect—are disabled. Join & leave messages, advancements, and coordinates are disabled. Totems of undying are also not allowed in this gamemode. Every time a player dies, a universal death cannon sounds, giving confirmation to players that someone has died, although they might not know exactly who.

If a player puts on a piece of armor, they will begin to take damage. This mechanic cements this SMP as notoriously difficult, where seasoned players will likely have the edge. Ultra Hardcore (UHC) mechanics are optional, where natural regeneration is disabled and players can only heal via golden apples, suspicious stews, and potions.

## Getting Started

### Dependencies & Enhancements

* Install the latest version of Skript on the SpigotMC website [here](https://www.spigotmc.org/resources/skript.114544/) (note that the latest version often requires the most recent build of Minecraft).
* You must have Java 17 or later installed on your server for Skript to function.
* Install Simple Voice Chat [here](https://modrinth.com/plugin/simple-voice-chat/versions) for both your server and your client (ex. Paper jar goes in the server's ```/plugins``` folder, while Fabric jar goes in your own ```/mods``` folder). All members must install Simple Voice Chat on their client.
* Open an additional port on your server. Navigate to ```plugins/voicechat/voicechat-server.properties``` and set the "port" value to that additional port. Restart the server to apply the changes.
* It's recommended to use a Hardcore Hearts texture pack [like this one](https://modrinth.com/resourcepack/hardcore-hearts) to enhance your experience.

### Installing

* Download the ```naked_and_afraid.sk``` file, and place it in ```plugins/Skript/scripts/naked_and_afraid.sk```.
* Follow the configuration instructions at the top of the file, or customize them to your preference.

### Finishing Up

* Once you have tested everything and are ready to begin, enable the Hardcore mechanics in the ```naked_and_afraid.sk``` file by removing the hashtags at the bottom of the "Death System" section.
* Enjoy!

## Author

Created by [Enzec](https://enzec.net)

## Version History

* 1.1
    * Disabled totems of undying
    * Elytras, skeleton skulls, and other non-armor items can now be worn without damaging the player
    * Chat-related commands have been disabled
    * Added a startup and shutdown message
* 1.0
    * Initial Release
 
## To Do

* Fix the tablist visibility issue
* Disable dispensers from dispensing armor

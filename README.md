# <img src="https://user-images.githubusercontent.com/40789489/106369491-386bf780-6352-11eb-8cad-c760d7f694b1.png" height=32 alt="Logo"></img> litetex's XVM config
Looks like normal WOT with minor improvements.

## [Download](https://downgit.github.io/#/home?url=https://github.com/litetex/xvm_config/tree/master/config)
If the above link doesn't work, try [downloading the repository as zip](https://github.com/litetex/xvm_config/archive/master.zip) and use the ``config`` folder

### Quick setup guide
* Requires [XMV](https://modxvm.com/en/download-xvm/)
* Download the config and install it in ``<WorldOfTanksInstallationDirectory>/res_mods/config/xvm/<configName>``
* Create/Override the ``<WorldOfTanksInstallationDirectory>/res_mods/config/xvm/xvm.xc`` file with the following content:
  ```xc
  ${"<configName>/@xvm.xc":"."}
  ```

## Features
* Hangar 
  * Cleaner interface
    * No referral Button
    * No daily quests visible
    * No "Combat Intelligence" / news messages
  * Crew auto return
  * Blocks the vehicle if ammo is low
  * Statistics for tanks
* Tank tooltips (Hangar/Techtree)
  * More information when hovering over the tank, e.g. speedlimit, terrain resistance, crewroles, ...
* Battle 
  * Shows last seen HP status of allies and enemies (when pressing the alt key)
  * Disables dogtags
  * Shows current time (upper left corner)
  * Shows stats of players (when networking mode is enabled)
* Service record
  * More/Improved statistics (when networking mode is enabled)
* Battle-Results
  * Better summary/Shows crew experience
* Minimap 
  * Custom circles with more friendly colors

## Example views
*Note: Network services are enabled in the screenshots*

![garage](https://user-images.githubusercontent.com/40789489/106368212-474dac80-6348-11eb-87fb-72d3ae0351ee.png "Garage")

![battle](https://user-images.githubusercontent.com/40789489/106368205-4288f880-6348-11eb-9b6f-eef30429a81d.png "Battle")
![battle_more_info](https://user-images.githubusercontent.com/40789489/106368211-461c7f80-6348-11eb-83f1-2c3779281685.png "Battle - More info (Alt key)")
![battle_basecap](https://user-images.githubusercontent.com/40789489/106368210-44eb5280-6348-11eb-8098-d391870fcd17.png "Battle - Base capture")
![battle_advanced_info](https://user-images.githubusercontent.com/40789489/106368208-43ba2580-6348-11eb-821a-ac03421dab5f.png "Battle - Overview (Tab key)")

![techtree](https://user-images.githubusercontent.com/40789489/106368605-3e120f00-634b-11eb-9af5-0bbf899c6e94.png "Techtree")
![service_record_vehicles](https://user-images.githubusercontent.com/40789489/106368215-487ed980-6348-11eb-85ec-449feb8804f0.png "Service record")

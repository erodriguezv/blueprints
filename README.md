# blueprints

Blueprints for Home Assistant

## Sonoff Switchman R5 scene controller
[ITEAD website](https://itead.cc/product/sonoff-switchman-scene-controller-r5/)

### Requirements
The blueprint requires that your sonoff R5 entity exists in home assistant through the HACS sonoff LAN integration (https://github.com/AlexxIT/SonoffLAN).

Many thanks to https://github.com/AlexxIT for that. 

The integration needs to be configured in auto mode (R5 is not supported in local only mode, at least to date)

The R5 also requires to be paired through the eWelink app to any of M5 smart switch, S40/S40 Lite smartplug, eWeLink-Remote gateway as a sort of bridge. (Select device in ewelink, go to it's configs and look for subdevices option). It also requires that the "bridge" device is in a fair range and up.
 
Once your R5 is linked to your "Bridge" device, it should show in the HACS sonoff integration, and you can start using the blueprint.

### Blueprint Installation
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Ferodriguezv%2Fblueprints%2Fblob%2Fmain%2Fsonoff_switchman_r5.yaml)

If the above link does not work, you can manually add the blueprint. Download the yaml file [sonoff_switchman_r5.yaml](https://raw.githubusercontent.com/erodriguezv/blueprints/main/sonoff_switchman_r5.yaml) and put it in your home assitant "config/blueprints/automation/homeassistant" folder.

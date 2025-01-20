
# Spotify media controller for Guition 480x480 screen via ESPHome

Installable via ESPHome this code offers the ability to view what is currently playing through a Home Assistant Spotify media_player entity, and send basic controls back to Home Assistant.

Currently artwork is not displayed due to lack of support for JPG images in LVGL/ESPHome's online_image 

Update the substitution at the top of the YAML with your entity ID and you should be good to go.


## Installation

Install my-project via ESPHome either in your HA setup or via CLI, you will need to add your wifi/ota/api details to the yaml.

You will also need to replace the spotify_entity with you HA Entity

```bash
  substitutions:
    spotify_entity: media_player.spotify_xxx # Replace with your HA media_player entity 
```
    
## Contributing

Contributions are always welcome!

This has only been tested with my setup, so feel free to open an issue if you come across anything.


## Preview

![App in action](https://community-assets.home-assistant.io/optimized/4X/9/1/7/9172240461046f8b33577e22274254cb1f0a0832_2_445x500.jpeg)


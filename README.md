# Home Assistant

Home Assistant scripts and automations.

## Scripts

* [Scene Turn Off](script/scene_turn_off.yaml) - Turn off all entities that are attached to this scene.
* [Text-to-Speech on Sonos](script/sonos_say.yaml) - Announces the provided message on the specified speaker.
* [Play on Sonos](script/sonos_play.yaml) - Plays the media on the specified speaker.

## Automations

* [Motion-activated Light Scene](automation/motion_time_based_light_scene.yaml) - Turn on a light scene using motion activation.
  * Depends on script [Scene Turn Off](script/scene_turn_off.yaml) with ID `script.scene_turn_off`
* [Alarm detection & notifier](automation/alarm_trigger.yaml) - Trigger actions based on the type of sensors (smoke or moisture).

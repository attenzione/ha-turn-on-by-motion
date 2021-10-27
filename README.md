Home Asssistant Blueprint for Motion Sensor
=======================

Turn on a light, switch, scene, script or group based on motion detection, and low light level.
Required entities:
- Motion sensor (single sensor or group)
- Target entity (light, switch, scene or script)

Optional features:
- You can set a cutoff entity of which the value determines whether the illuminance level is low and the automation needs to trigger. 
- You can define a blocking entity, which blocks the automation from running when this entity's state is on. 
- You van define a turn-off blocking entity, which blocks the entity from turning off after the set delay. 
- Time limits can also be defined to limit the time before and after the automation should trigger. 
- If you want the entity to turn off after a certain amount of seconds, you can use the Wait Time input. 
- If you want another entity than the target_entity to turn off after the delay, you can define a separate Turn-off entity. 
- If you do not enable the optional entities the automation will skip these conditions."

Source: https://community.home-assistant.io/t/motion-activated-entity-optional-lux-sensor-time-of-day-blocking-boolean/298080

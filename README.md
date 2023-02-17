# Overview
This repository contains the real world IoT smart-home dataset that was used in the paper "ARGUS: Context-Based Detection of Stealthy IoT Infiltration Attacks". The dataset contains the status changes of all IoT devices deployed in 5 different smart-homes.
The dataset covers different smart-home settings and living situations, including a room with a single inhabitant in a shared flat (Home1), a one-room appartment (Home 2), as well as 3 larger homes with 4 inhabitants each (Home3, Home4, Home5). A detailed description of the settings is provided in the paper.

The corresponding paper was published as Rieger, Chilese, Mohamed, Miettinen, Fereidooni, Sadeghi "ARGUS: Context-Based Detection of Stealthy IoT Infiltration Attacks" at USENIX Security 2023.  [Paper available here.](https://arxiv.org/abs/2302.07589)

```bibtex
@inproceedings{rieger2023argus,
  title={{ARGUS: Context-Based Detection of Stealthy IoT Infiltration Attacks}},
  author={Rieger, Phillip and Chilese, Marco and Mohamed, Reham and Miettinen, Markus and Fereidooni, Hossein and Sadeghi, Ahmad-Reza},
  booktitle={32nd USENIX Security Symposium (USENIX Security 23)},
  year={2023},
  publisher = {USENIX Association}
}
```

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

# Devices
The individual homes contain in particular the following devices:

## Home1
* automation.cameraOffWhenAtHome
* automation.cameraOnWhenUserLeave
* automation.lightsOffWhenTooBright
* automation.lightsOnWhenMotionDetected
* camera.status
* ceilingLamp
* co2.status
* co2.value
* deskLamp
* door
* humidity
* ipCamera.LightLevel
* ipCamera.motion
* ipCamera.motionActive
* ipCamera.sound
* person.home
* phone.activity
* phone.atHome
* phone.charging
* phone.sleepConfidence
* phone.wifiConnection
* rolo.position
* sun
* temperature
* thermostat.heatingTemperature
* thermostat.measuredTemperature
* weather.homeLocation
* weather.town
* window

## Home2
* automation.lightOnInTheMorning
* automation.lightsOffInTheEvening
* automation.lightsOffWhenTooBright
* automation.lightsOnWhenMotionDetected
* camera.status
* ceilingLamp
* deskLamp
* door
* hue.lightLevel
* hue.motionSensor.motion
* hue.temperature
* humidity
* ipCamera.LightLevel
* ipCamera.motion
* ipCamera.motionActive
* ipCamera.sound
* person.home
* phone.activity
* phone.atHome
* phone.batteryLife
* phone.lightSensor
* phone.phoneStatus
* phone.sleepConfidence
* phone.wifiConnection
* sun
* temperature
* thermostat.heatingTemperature
* thermostat.measuredTemperature
* weather.homeLocation
* window

## Home3
* automation.cameraOnWhenUserLeave
* camera.status
* ceilingLamp
* deskLamp
* door
* hue.lightLevel
* hue.motionSensor.motion
* hue.temperature
* hue2.lightLevel
* hue2.motion
* hue2.temperature
* hueWhiteLamp3
* huewhiteLamp2
* ipCamera.LightLevel
* ipCamera.motion
* ipCamera.motionActive
* ipCamera.sound
* light.livingRoom
* radiatorThermostat.measuredTemperature
* sun
* weather.homeLocation
* weather.town
* window

## Home4
* automation.cameraOffWhenAtHome
* automation.cameraOnWhenUserLeave
* automation.dinnerLights
* automation.lightsOffWhenNoMotion
* automation.lightsOffWhenTooBright
* automation.lightsOnWhenMotionDetected
* ceilingLamp
* climate.controllAccessPoint
* climateControll.heating
* controll.accessRoom1
* deskLamp
* door
* hue.lightLevel
* hue.motionSensor.motion
* hue.temperature
* humidity
* ipCamera.LightLevel
* ipCamera.motion
* ipCamera.motionActive
* ipCamera.sound
* person.home
* phone.activity
* phone.atHome
* phone.locked
* phone.sleepConfidence
* phone.sleepSegment
* phone.wifiConnection
* sun
* temperature
* thermostat.heatingTemperature
* thermostat.measuredTemperature
* weather.homeLocation
* weather.town
* window

## Home5
* automation.allLightsOff
* automation.allLightsOn
* automation.dinnerLights
* automation.dinnerTableLights
* automation.gamingMode
* automation.heatingBoostOff
* automation.lightsOffWhenNoMotion
* automation.pianoLight
* automation.sofaLamp
* automation.studioLightOff
* automation.studioLightOnWhenMotion
* ceilingLamp
* climate.controllAccessPoint
* climateControll.heating
* deskLamp
* door
* hue.lightLevel
* hue.motionSensor.motion
* hue.temperature
* humidity
* ipCamera.LightLevel
* ipCamera.motion
* ipCamera.motionActive
* ipCamera.pressure
* ipCamera.sound
* lamp.consumption
* lamp.current
* lamp.dailyConsumption
* lamp.totalConsumption
* lamp.voltage
* phone.activity
* phone.charging
* phone.locked
* sun
* temperature
* thermostat.measuredTemperature
* wheather.town

## Usage

Sync the color of your build (red if failed, green if passing) with your Travis CI builds using your Philips Hue lights. Currently this has basic functionality, if the Travis CI build passes, your Hue lights will turn green, if your Travis CI build fails it will turn red. 

There's currently a Ruby and a Python Hue Bridge client included in this repo.

## TODO

* Synchronize Rules
* Synchronize Scenes
* Synchronize Schedules
* Synchronize Sensors
Trigger changes on states on/off, bri (level), hue, sat, xy, ct, alert, effect and transitiontime/cron job triggering

## Example

Failing build in Travis CI:

![image](https://user-images.githubusercontent.com/20936398/171348593-f62800e2-a6c8-46dd-91da-aafd962ba5ec.png)

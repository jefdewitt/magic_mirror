# Magic Mirror

Magic Mirror is a smart mirror featuring a built-in display that shows weather, time, current temperature, and more. I used a a Raspberry Pi 3 and a hand built wooden frame with an LCD mounted behind glass overlayed with mirror window tint. I built my Magic Mirror based on Micheal Teeuw's own Magic Mirror [project](https://www.raspberrypi.org/blog/magic-mirror/), including repo files and available documentation.

## Requirements

- Raspberry Pi 3 flashed with the latest Raspian OS
- Frame
- LCD 
- One-way mirror
- MagicMirror² repository files

### Additional Repo Clone Instructions

- Install `Node.js`
- Clone the repo and check out the beta branch: `git clone https://github.com/MichMich/MagicMirror`
- Enter the repo: `cd ~/MagicMirror`
- Install and run the app: `npm install && npm start`

## Modules

- [**Clock**](modules/default/clock)
- [**Calendar**](modules/default/calendar)
- [**Current Weather**](modules/default/currentweather)
- [**Weather Forecast**](modules/default/weatherforecast)
- [**News Feed**](modules/default/newsfeed)
- [**Compliments**](modules/default/compliments)
- [**Hello World**](modules/default/helloworld)
- [**Alert**](modules/default/alert)

## Important Terminal Commands

- `sudo shutdown -r now` Shutdown and restart the Pi
- `DISPLAY=:0 nohup npm start &` Starts the display

## Screenshot

![Magic Mirror app image](/magic-mirror-without-mirror.jpg?raw=true "Magic Mirror app image")

## Comments

Any questions or comments please send them my way [here](http://www.jefdewitt.com/connect).



# fivem-seatbelt

Original script: [fivem-seatbelt](https://github.com/IndianaBonesUrMom/fivem-seatbelt)

Developed last night on a live server. Hilarious AF so decided to share.  

Demo: <https://gyazo.com/e04eb4641f0f3674912b2b6a1c4cba93>

Launches player through the windshield if a huge change in velocity happens (eg. crash).  

Press K to enable / disable seatbelts.
Make a copy of locales/en.js and edit it to change language. Don't forget to update Config.Locale in config.lua and client_scripts in __resource.lua!

Note: You have to open your seatbelt to leave the vehicle.

## Download

### 1) Using [fvm](https://github.com/qlaffont/fvm-installer)

``` sh
fvm install --save explodingpineapple-fivem/fivem-seatbelt
```

### 2) Using Git

``` sh
cd resources
git clone https://github.com/explodingpineapple-fivem/fivem-seatbelt.git
```

### 3) Manually

- Download <https://github.com/explodingpineapple-fivem/fivem-seatbelt/archive/master.zip>
- Extract it into your resources directory

## Installation

Add `start esx_voice` to your server.cfg
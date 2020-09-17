<span align="center">

<a href="https://github.com/homebridge/verified/blob/master/verified-plugins.json"><img alt="homebridge-verified" src="https://raw.githubusercontent.com/homebridge-plugins/homebridge-honeywell-home/master/honeywell/Homebridge_x_Honeywell.svg?sanitize=true" width="500px"></a>

# Homebridge Honeywell Home Room Sensor

<a href="https://www.npmjs.com/package/homebridge-honeywell-home-roomsensor"><img title="npm version" src="https://badgen.net/npm/v/homebridge-honeywell-home-roomsensor" ></a>
<a href="https://www.npmjs.com/package/homebridge-honeywell-home-roomsensor"><img title="npm downloads" src="https://badgen.net/npm/dt/homebridge-honeywell-home-roomsensor" ></a>

The **Homebridge Honeywell Home Room Sensor** plugin is and add-on to the [**Homebridge Honeywell Home**](https://www.npmjs.com/package/homebridge-honeywell-home) plugin.

**Homebridge Honeywell Home Room Sensor** plugin allows you to access your T9 Honeywell Home thermostat room sensor(s) from HomeKit.

</p>

</span>

## Installation

1. Search for "Honeywell Home Roomsensor" on the plugin screen of [Homebridge Config UI X](https://github.com/oznu/homebridge-config-ui-x).
2. Click **Install**.

## Configuration

1. Login / create an account at https://developer.honeywellhome.com/user
2. Click **Create New App**
3. Give your application a name, and enter the Callback URL as `https://homebridge-honeywell.iot.oz.nu/link-account`
4. Enter the generated consumer key and secret into the plugin settings screen of [Homebridge Config UI X](https://github.com/oznu/homebridge-config-ui-x)
5. Click **Link Account**

  <p align="center">

  <img src="https://user-images.githubusercontent.com/9875439/90537529-0b7cad00-e143-11ea-8c49-6820ccdec3bb.png" width="600px">

  </p>

## Homebridge Honeywell Home Plugins

- [homebridge-honeywell-home](https://github.com/donavanbecker/homebridge-honeywell-home)
  - The Homebridge Honeywell Home plugin allows you to access your Honeywell Home thermostat from HomeKit.
  - This Plugin is the main plugin that all other plugins root from. This combines all the plugins together.
- [homebridge-honeywell-home-thermostat](https://github.com/donavanbecker/homebridge-honeywell-home-thermostat)
  - The Homebridge Honeywell Home Thermsotat plugin allows you to control your Honeywell Home thermostats from HomeKit.
- [homebridge-honeywell-home-roomsensor](https://github.com/donavanbecker/homebridge-honeywell-home-roomsensor)
  - The Homebridge Honeywell Home Room Sensor plugin allows you to access your T9 Honeywell Home thermostat Room Sensor from HomeKit.
- [homebridge-honeywell-home-roomsensor-thermostat](https://github.com/donavanbecker/homebridge-honeywell-home-roomsensor-thermostat)
  - The Homebridge Honeywell Home Room Sensor Thermostat plugin allows you to access your T9 Honeywell Home thermostat room sensor as a thermostat from HomeKit. This will allow you to set that room as priority in your house.
- [homebridge-honeywell-home-leaksensor](https://github.com/donavanbecker/homebridge-honeywell-leak)
  - The Homebridge Honeywell Home Leak Sensor plugin allowas you to access your Honeywell Leak Detector / Residio Droplet from HomeKit.

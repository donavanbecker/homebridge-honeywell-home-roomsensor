# Changelog

All notable changes to this project will be documented in this file. This project uses [Semantic Versioning](https://semver.org/)

## [Version 2.1.0](https://github.com/donavanbecker/homebridge-honeywell-home-roomSensor/compare/v2.0.1...v2.1.0) (2020-08-29)

### Changes

- If device is no longer Alive or Active it will automatically be removed.

## [Version 2.0.1](https://github.com/donavanbecker/homebridge-honeywell-home-roomSensor/compare/v2.0.0...v2.0.1) (2020-08-24)

### Changes

- Small code changes.
- Update dependencies.

## [Version 2.0.0](https://github.com/donavanbecker/homebridge-honeywell-home-roomSensor/compare/v1.2.0...v2.0.0) (2020-08-19)

### Major Changes

- Added Battery Service which allows the option to hide temperature Sensor(s).

### Changes

- Added the Option to Hide Temperature Sensor(s).
- Removed StatusActive Service.

## [Version 1.2.0](https://github.com/donavanbecker/homebridge-honeywell-home-roomSensor/compare/v1.1.2...v1.2.0) (2020-08-18)

### Changes

- Added the Option to Hide Occupancy Sensor(s), Motion Sensor(s), and Humidity Sensor(s).

## [Version 1.1.2](https://github.com/donavanbecker/homebridge-honeywell-home-roomSensor/compare/v1.1.1...v1.1.2) (2020-08-11)

### Changes

- Updated `package.json`.

## [Version 1.1.1](https://github.com/donavanbecker/homebridge-honeywell-home-roomSensor/compare/v1.1.0...v1.1.1) (2020-08-11)

### Changes

- Updated `package.json`.

## [Version 1.1.0](https://github.com/donavanbecker/homebridge-honeywell-home-roomSensor/compare/v1.0.1...v1.1.0) (2020-07-30)

### Changes

- If refresh token expires, the new refresh token that is fetched will now be saved to `config.json`.
- Changed some logging and debug logging.
- Update github links for NPM.

## [Version 1.0.1](https://github.com/donavanbecker/homebridge-honeywell-home-roomSensor/compare/v1.0.0...v1.0.1) (2020-07-29)

### Changes

- Changed loggging on refresh and access token to warn logs, so they can be viewed in yellow.

## [Version 1.0.0](https://github.com/donavanbecker/homebridge-honeywell-home-roomSensor/releases/tag/v1.0.0) (2020-07-27)

### Major Changes

- This plugin allows you to be able to view your Honeywell T9/T10 Room Sensor inside HomeKit.
- This plugin is an add-on to the [Homebridge Honeywell Home plugin](https://github.com/donavanbecker/homebridge-honeywell-home).

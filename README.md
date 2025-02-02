# Pinkywafer Home Assistant Config

[![GitHub Actions][actions-shield]][actions]

[![Support Pinkywafer on Patreon][patreon-shield]][patreon]
[![Buy me a coffee][bmc-shield]][bmc]

This is my live Home Assistant config. 
It has recently migrated to my HP Proliant server.
Proxmox is installed on bare metal,  then this (production) Home Assistant runs in a VM.
A separate VM provides my Dev. env
Various other VMs and LXCs are providing other services such as Plex server, NAS etc on this same machine

This repo is checked using Github Actions for continuous integration.
  * The config is first checked with yamllint and remarklint.
  * The config is validated against the currently installed version of Home Assistant, the latest release of Home Assistant, the latest beta release of Home Assistant and the Latest Home Assistant Dev branch.
  * ESPHome yaml is also validated against the latest version of ESPHome

***

## Some statistics about my installation:

Lines of yaml code in my configuration (excluding secrets): 7878

Number of entities: 873

Type | Qty
-- | --
Alarm Control Panel | 1
Alert | 2
Automation | 86
Binary Sensor | 140
Camera | 14
Device Tracker | 37
Group | 1
Input Boolean | 3
Input Datetime | 5
Input Text | 8
Light | 33
Media Player | 24
Person | 3
Scene | 1
Script | 26
Sensor | 417
Sun | 1
Switch | 46
Weather | 1
Zone | 4

***

## HACS installed components

### Integrations
  - [Anniversaries](https://github.com/pinkywafer/Anniversaries)
  - [Authenticated](https://github.com/custom-components/authenticated)
  - [Browser Mod](https://github.com/thomasloven/hass-browser_mod)
  - [Calendarific](https://github.com/pinkywafer/Calendarific)
  - [Garbage Collection](https://github.com/bruxy70/Garbage-Collection)
  - [Generate Readme](https://github.com/custom-components/readme)
  - [Google Home](https://github.com/leikoilja/ha-google-home)
  - [Ha Omada](https://github.com/zachcheatham/ha-omada)
  - [HACS](https://github.com/hacs/integration)
  - [Plex Assistant](https://github.com/maykar/plex_assistant)
  - [Reolink Ip Camera](https://github.com/fwestenberg/reolink_dev)
  - [Spacex Next Launch And Starman](https://github.com/djtimca/HASpaceX)
  - [Spotcast](https://github.com/fondberg/spotcast)
  - [Xmr Pool Statistics](https://github.com/hwmland/homeassistant-xmrpool_stat)
  - [Youtube](https://github.com/custom-components/youtube)

### Lovelace
  - [Button Card](https://github.com/custom-cards/button-card)
  - [Card Mod](https://github.com/thomasloven/lovelace-card-mod)
  - [Card Tools](https://github.com/thomasloven/lovelace-card-tools)
  - [Entity Attributes Card](https://github.com/custom-cards/entity-attributes-card)
  - [Fold Entity Row](https://github.com/thomasloven/lovelace-fold-entity-row)
  - [Github Card](https://github.com/ljmerza/github-card)
  - [Layout Card](https://github.com/thomasloven/lovelace-layout-card)
  - [Lovelace Card Preloader](https://github.com/gadgetchnnel/lovelace-card-preloader)
  - [Mini Graph Card](https://github.com/kalkih/mini-graph-card)
  - [Mini Media Player](https://github.com/kalkih/mini-media-player)
  - [Multiple Entity Row](https://github.com/benct/lovelace-multiple-entity-row)
  - [Simple Weather Card](https://github.com/kalkih/simple-weather-card)
  - [Slider Entity Row](https://github.com/thomasloven/lovelace-slider-entity-row)
  - [Time Picker Card](https://github.com/GeorgeSG/lovelace-time-picker-card)

***


Generated by the [custom readme integration](https://github.com/custom-components/readme)

[actions]: https://github.com/pinkywafer/Home-Assistant_Config/actions
[bmc]: https://www.buymeacoffee.com/V3q9id4
[patreon]: https://www.patreon.com/pinkywafer
[actions-shield]: https://github.com/pinkywafer/Home-Assistant_Config/workflows/Home%20Assistant%20CI/badge.svg
[bmc-shield]: https://img.shields.io/static/v1.svg?label=Buy%20me%20a%20coffee&logo=buy%20me%20a%20coffee&logoColor=white&labelColor=ff69b4&message=donate&color=Black
[patreon-shield]: https://c5.patreon.com/external/logo/become_a_patron_button.png

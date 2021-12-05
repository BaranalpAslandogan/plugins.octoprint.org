---
layout: plugin

id: printox
title: OctoPrint-Printox
description: Plugin for cascading printing via esp32
authors:
  - Baranalp Aslandoğan
license: AGPLv3

date: 2021-11-30

homepage: https://github.com/BaranalpAslandogan/OctoPrint-Printox
source: https://github.com/BaranalpAslandogan/OctoPrint-Printox
archive: https://github.com/BaranalpAslandogan/OctoPrint-Printox/archive/master.zip

tags:
  - printox
  - rapid print
  - esp32
  - queue

compatibility:
  python: ">=2.7,<4"
  os:
    - linux
    - windows
    - macos
    - freebsd
  octoprint:
    - 1.2.0

screenshots:
  - url: /assets/img/plugins/printox/main_1.png
    alt: Plugin in idle status
    caption: Main screen
  - url: /assets/img/plugins/printox/main_2.png
    alt: Print ejecting on progress
    caption: Finishing print
  - url: /assets/img/plugins/printox/main_3.png
    alt: Print queue done
    caption: change queue state to idle
---

This plugin allows your multiple prints to be kicked out of bed via ESP32 with a custom platter mechanism. With this plugin, you can create multiple queues, delete an existing queue or update a queue of your choice. The plugin can work without ESP32, but you have to manually unmount the print every time you print.

## Prerequisites

Tinydb, Asyncio and Websockets packages must be installed for Python.

## Setup

Install the plugin via the bundled [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager)
or manually using this URL:

    https://github.com/BaranalpAslandogan/OctoPrint-Printox/archive/master.zip

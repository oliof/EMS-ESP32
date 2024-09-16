# ![logo](media/EMS-ESP_logo_dark.png)

[![version](https://img.shields.io/github/release/emsesp/EMS-ESP32.svg?label=Latest%20Release)](https://github.com/emsesp/EMS-ESP32/blob/main/CHANGELOG.md)
[![release-date](https://img.shields.io/github/release-date/emsesp/EMS-ESP32.svg?label=Released)](https://github.com/emsesp/EMS-ESP32/commits/main)
[![license](https://img.shields.io/github/license/emsesp/EMS-ESP32.svg)](LICENSE)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=emsesp_EMS-ESP32&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=emsesp_EMS-ESP32)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/9441142f49424ef891e8f5251866ee6b)](https://app.codacy.com/gh/emsesp/EMS-ESP32/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![downloads](https://img.shields.io/github/downloads/emsesp/EMS-ESP32/total.svg)](https://github.com/emsesp/EMS-ESP32/releases)
[![chat](https://img.shields.io/discord/816637840644505620.svg?style=flat-square&color=blueviolet)](https://discord.gg/3J3GgnzpyT)

[![GitHub stars](https://img.shields.io/github/stars/emsesp/EMS-ESP32.svg?style=social&label=Star)](https://github.com/emsesp/EMS-ESP32/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/emsesp/EMS-ESP32.svg?style=social&label=Fork)](https://github.com/emsesp/EMS-ES32P/network)
[![donate](https://img.shields.io/badge/donate-PayPal-blue.svg)](https://www.paypal.com/paypalme/prderbyshire/2)

**EMS-ESP** is an open-source firmware for the Espressif ESP32 microcontroller that communicates with **EMS** (Energy Management System) based equipment from manufacturers like Bosch, Buderus, Nefit, Junkers, Worcester and Sieger. It requires a small gateway circuit to interface with the EMS bus which can be purchased from <https://bbqkees-electronics.nl> or custom built.

## **Key Features**

- A multi-user, multi-language web interface to change settings and monitor incoming data
- An advanced console, accessible via Serial/USB or Telnet for more operations and monitoring
- Native integration with Home Assistant, Domoticz, openHAB and Modbus
- Easy setup and install with automatic updates
- Supporting over 120 different EMS compatible devices from thermostats, boilers, heat pumps, mixing units, solar modules from brands as Bosch, Buderus, Nefit, Junkers, Worcester and Sieger
- Simulate remote thermostats
- Localized to 10 languages, and customizable to change names to your preference
- Extendable via adding external modules or adding your own custom entities directly within the WebUI
- A powerful scheduler to automate tasks and trigger events based data changes
- A Notification service to alert you of important events

## **Installing**

For a quick install of the latest stable release go to [https://install.emsesp.org](https://install.emsesp.org). For other methods of installing and upgrading, and switching to the development version go to the section in the [documentation](https://emsesp.org).

## **Documentation and Wiki**

Visit [emsesp.org](https://emsesp.org) for details on how to install and configure EMS-ESP.

## **Getting Support**

To chat with the community reach out on our [Discord Server](https://discord.gg/3J3GgnzpyT).

If you like **EMS-ESP**, please give it a ✨ on GitHub, or even better fork it and contribute. You can also offer a small donation. This is an open-source project maintained by volunteers, and your support is greatly appreciated.

## **Live Demo**

For a live demo go to [demo.emsesp.org](https://demo.emsesp.org). Pick a language from the sign on page and log in with any username or password. Note not all features are operational as it's based on static data.

## **Contributors**

EMS-ESP is a project created by [proddy](https://github.com/proddy) and owned and maintained by both [proddy](https://github.com/proddy) and [MichaelDvP](https://github.com/MichaelDvP) with support from [BBQKees Electronics](https://bbqkees-electronics.nl).

## **Libraries used**

- [esp8266-react](https://github.com/rjwats/esp8266-react) by @rjwats for the core framework that provides the Web UI, which has been heavily modified
- [uuid-\*](https://github.com/nomis/mcu-uuid-console) from @nomis. The console, syslog, telnet and logging are based off these awesome open source libraries
- [ArduinoJson](https://github.com/bblanchon/ArduinoJson) for all the JSON processing
- [espMqttClient](https://github.com/bertmelis/espMqttClient) for the MQTT client
- ESPAsyncWebServer and AsyncTCP for the Web server and TCP backends, with custom modifications for performance

## **License**

This program is licensed under GPL-3.0

## **Screenshots**

### Web Interface

|                                    |                                  |
| ---------------------------------- | -------------------------------- |
| ![Web Settings](media/web_settings.png) | ![Web Status](media/web_status.png) |
| ![Web Devices](media/web_devices.png)  | ![Web MQTT](media/web_mqtt.png)   |
| ![Web Edit](media/web_edit.png)     | ![Web Log](media/web_log.png)    |

### Telnet Console

![Console](media/console0.png)

### Home Assistant

![Home Assistant](media/ha_lovelace.png)

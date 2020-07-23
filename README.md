[![Let's FIWARE Banner](https://github.com/lets-fiware/fiware-sakuraio/blob/gh-pages/images/lets-fiware-logo-non-free.png)](https://www.letsfiware.jp/)

[![License: MIT](https://img.shields.io/github/license/lets-fiware/fiware-sakuraio.svg)](https://opensource.org/licenses/MIT)

# FIWARE-sakuraio

## Bridge for NGSI

There are several bridges to connect the sakura.io to the FIWARE system.

- NGSI Adapter for sakura.io (Webhook)
- NGSI Adapter for sakura.io (WebSocket)
- IoT Agent for sakura.io

You can choose a bridge that suits your requirements.

| Bridge for NGSI                        | Message Payload                                   | Transport Mechanism | OSS License      |
| ---------------------------------------| ------------------------------------------------- | ------------------- | ---------------- |
| NGSI Adapter for sakura.io (Webhook)   | sakura.io channels                                | HTTP                | MIT license      |
| NGSI Adapter for sakura.io (WebSocket) | sakura.io channels                                | WebSocket           | MIT license      | 
| IoT Agent for sakura.io                | UltraLight based protocol over sakura.io channels | WebSocket           | AGPL-3.0 license |

## IoT Device

- IoT Device for sakura.io channels
- IoT Device for UltraLight

## How to connect sakura.io to FIWARE system

- https://www.letsfiware.jp/dev/fiware-sakuraio-ngsi-adapter/ (in Japanese)
- https://www.letsfiware.jp/dev/fiware-sakuraio-ngsi-adapter-webhook/ (in Japanese)

## Source Code

The source code of NGSI Adapter is in this repository. The source code of IoT Agent for sakura.io is
[here](https://github.com/lets-fiware/custom-iotagent-sakuraio).

## About sakura.io

[SAKURA internet Inc.](https://www.sakura.ad.jp/en/corporate/) is a provider of internet infrastructures in Japan.
They provides [sakura.io service](https://sakura.io/). It's composed the sakura.io platform and communication module.
The communication module supports 4G-LTE data communication and it can be attached on Raspberry Pi, Arduino and so on.

![](https://github.com/lets-fiware/fiware-sakuraio/blob/gh-pages/images/sakuraio-module-on-raspberrypi-non-free.png)

### Reference
-    [sakura.io - GitHub](https://github.com/sakuraio)
-    [sakura.io documents](https://sakura.io/docs/)

## Copyright and License

Copyright (c) 2020 Kazuhito Suda<br>
Licensed under the MIT license.

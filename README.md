# My personal Home Assistan config files 🏠🤖

![GitHub Repo stars](https://img.shields.io/github/stars/WillemSpork/home-assistant-config)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/WillemSpork/home-assistant-config/main)
[![HA Version](https://img.shields.io/badge/Running%20Home%20Asssistant-2024.12.3%20-darkblue)](https://github.com/home-assistant/core/releases)

## My Devices

<table>
    <thead>
        <tr>
            <th>Switches 🎚</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Aqara Wireless Mini Switch</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Philips Hue Wall Switch Module</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Philips Hue Dimmer switch</td>
            <td>2</td>
        </tr>
        <tr>
            <td>Nodon Zigbee Relais</td>
            <td>1</td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Sensors 🌡️</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Aqara Door Sensor</td>
            <td>2</td>
        </tr>
        <tr>
            <td>Aqara Temperature Sensor</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Philips Motion Sensor</td>
            <td>2</td>
        </tr>
        <tr>
            <td>ESP32 Module</td>
            <td>3</td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Media 🎧</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Apple TV 4K</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Sonos One SL</td>
            <td>2</td>
        </tr>
        <tr>
            <td>Sonos Arc</td>
            <td>1</td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Lights 💡</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Philips Hue E27 White and Color</td>
            <td>10</td>
        </tr>
        <tr>
            <td>Philips Hue GU10 White and Color</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Philips Hue E14 White</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Philips Hue Go</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Philips Hue Lightstrip</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Philips Hue G40 globe</td>
            <td>1</td>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Others 🔗</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Aqara G4 Smart Wireless Video Doorbell</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Apple HomePod mini</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Google Nest Mini</td>
            <td>1</td>
        </tr>
        <tr>
            <td>SONOFF Zigbee 3.0 USB Dongle Plus-E</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Dyson Purifier humidify+cool</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Dyson Purifier cool</td>
            <td>1</td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
</table>

## Add-ons & plugins

<table>
    <thead>
        <tr>
            <th>Add-ons</th>
            <th>URL</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>AdGuard Home</td>
            <td>[link](https://github.com/hassio-addons/addon-adguard-home)</td>
        </tr>
        <tr>
            <td>AirCast</td>
            <td>link</td>
        </tr>
        <tr>
            <td>Cloudflared</td>
            <td>link</td>
        </tr>
        <tr>
            <td>MariaDB</td>
            <td>link</td>
        </tr>
        <tr>
            <td>Matter Server</td>
            <td>link</td>
        </tr>
        <tr>
            <td>Mosquitto Broker</td>
            <td>link</td>
        </tr>
        <tr>
            <td>Node-RED</td>
            <td>link</td>
        </tr>
        <tr>
            <td>PS5 MQTT</td>
            <td>link</td>
        </tr>
        <tr>
            <td>Studio Code Server</td>
            <td>link</td>
        </tr>
        <tr>
            <td>Terminal & SSH</td>
            <td>link</td>
        </tr>
        <tr>
            <td>UniFi Network Application</td>
            <td>link</td>
        </tr>
        <tr>
            <td>WireGuard</td>
            <td>link</td>
        </tr>
        <tr>
            <td>Zigbee2MQTT</td>
            <td>link</td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
</table>

## Todo

- Fix: lights in office won't respond to 'turn off' automations from sleepmode
- ~~Fix: Host (Intel NUC) needs a restart job every night~~ (no it doesn't)
- Add: ESP32 and pressure sensors in bed for sleepmode ([link](https://www.homeautomationguy.io/blog/making-my-own-bed-sensor))
- ~~Add: Reset states (sleepmode, etc) every night~~ (done)


## Thanks to

Many thanks to [@BasNijholt](https://github.com/basnijholt) for being an amazing inspiration in my setup and structeration.
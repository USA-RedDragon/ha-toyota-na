# ha-toyota-na

## Introduction

This is a Home Assistant integration for Toyota North America.

![GitHub release (latest by date)](https://img.shields.io/github/v/release/USA-RedDragon/ha-toyota-na?style=for-the-badge) ![GitHub Release Date](https://img.shields.io/github/release-date/USA-RedDragon/ha-toyota-na?style=for-the-badge) ![GitHub Releases](https://img.shields.io/github/downloads/USA-RedDragon/ha-toyota-na/latest/total?color=purple&label=%20release%20Downloads&style=for-the-badge)

## Current features

Sensors:

* Door lock status
* Window/Moonroof status
* Trunk Status
* Real time location
* Last Parked Location
* Tire Pressure
* Fuel Level
* Odometer
* Oil Status
* Key Fob Battery Status

Services:

* Lock/Unlock Doors
* Remote Start/Stop Engine

## Installation

### HACS

1. Install HACS: <https://hacs.xyz/docs/setup/download>
2. Using the 3-dot menu in the top right, select "Custom Repositories"
3. Add `https://github.com/USA-RedDragon/ha-toyota-na` as an Integration
4. Search and install "Toyota/Lexus (North America)" in HACS integration store

### Manual installation

#### Download the repo

Download this repo by either of the following methods

* `git clone https://github.com/USA-RedDragon/ha-toyota-na`
* Download <https://github.com/USA-RedDragon/ha-toyota-na/archive/refs/heads/main.zip>

#### Adding to Home Assistant

Copy or link this repo into Home Assistant `custom_components` directory

```bash
ln -s ha-toyota-na/custom_components/toyota_na ~/.homeassistant/custom_components/
```

## Configuration

Click "Add integration" from Home Assistant, search "Toyota (North America)", click to add.

Enter your username and password for Toyota One App or Toyota Entune App and all set.

After setting up, Most information in Toyota One app should be available in Home Assistant.
![image](https://user-images.githubusercontent.com/4755389/147372481-4d280b6e-6f61-434c-a768-f4a089f009c3.png)

## Credits

Thanks @DurgNomis-drol for making the the original [Toyota Integration](https://github.com/DurgNomis-drol/ha_toyota) and bringing up the discussion thread at <https://github.com/DurgNomis-drol/mytoyota/issues/7>.

Thanks @visualage for finding the way to authenticate headlessly.

Thanks @widewing for the upstream [ha-toyota-na](https://github.com/widewing/ha-toyota-na) integration.

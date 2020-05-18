# Grow HAT Mini

Designed as a tiny valet for your plants, Grow HAT mini will monitor the soil moiture for up to 3 plants, water them with tiny pumps, and show you their health on it's small but informative screen. Learn more - https://shop.pimoroni.com/products/grow

[![Build Status](https://travis-ci.com/pimoroni/enviroplus-python.svg?branch=master)](https://travis-ci.com/pimoroni/grow-python)
[![Coverage Status](https://coveralls.io/repos/github/pimoroni/grow-python/badge.svg?branch=master)](https://coveralls.io/github/pimoroni/grow-python?branch=master)
[![PyPi Package](https://img.shields.io/pypi/v/enviroplus.svg)](https://pypi.python.org/pypi/growhat)
[![Python Versions](https://img.shields.io/pypi/pyversions/enviroplus.svg)](https://pypi.python.org/pypi/growhat)

# Installing

You're best using the "One-line" install method.

## One-line (Installs from GitHub)

```
curl -sSL https://get.pimoroni.com/grow | bash
```

**Note** report issues with one-line installer here: https://github.com/pimoroni/get

## Or... Install and configure dependencies from GitHub:

* `git clone https://github.com/pimoroni/grow-python`
* `cd grow-python`
* `sudo ./install.sh`

**Note** Raspbian Lite users may first need to install git: `sudo apt install git`

## Or... Install from PyPi and configure manually:

* Run `sudo pip install growhat`

**Note** this wont perform any of the required configuration changes on your Pi, you may additionally need to:

* Enable i2c: `raspi-config nonint do_i2c 0`
* Enable SPI: `raspi-config nonint do_spi 0`

And install additional dependencies:

```
sudo apt install python-numpy python-smbus python-pil python-setuptools
```

## Help & Support

* GPIO Pinout - https://pinout.xyz/pinout/enviro_plus
* Support forums - http://forums.pimoroni.com/c/support
* Discord - https://discord.gg/hr93ByC
[![Bare Conductive](https://www.bareconductive.com/wp-content/uploads/2017/03/Bare-Conductive-LOGO_master_AW.png)](http://www.bareconductive.com/)

# Bare Conductive Pi Cap Simple Touch Utility

Example touch detection code for the [Bare Conductive Pi Cap](http://www.bareconductive.com/shop/pi-cap/). Writes simple touch / release event messages to stdout.

## Requirements

* Requires [WiringPi](http://wiringpi.com/) (`apt-get install wiringpi`)
* Requires [Bare Conductive's MPR121 libary for WiringPi](https://github.com/BareConductive/wiringpi-mpr121)

## Install / Build

* You should install this code as part of the Pi Cap Raspbian package: `sudo apt-get install picap`    
* However, if you are doing this yourself, clone the repository, enter it and run `make`

## Usage

    simple-touch

N.B. must be run as root    
    
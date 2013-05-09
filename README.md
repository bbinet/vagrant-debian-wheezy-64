## About

This script will: 

 1. download the Debian 7.0 "Wheezy" server, 64bit iso
 2. ... do some magic to turn it into a vagrant box file
 3. output package.box 

## Usage

    ./build.sh

This should do everything you need. If you don't have 
mkisofs, install [homebrew](http://mxcl.github.com/homebrew/), then:

    brew install cdrtools

### Notes

This script basted on original Carl's [repo](https://github.com/cal/vagrant-ubuntu-precise-64) and with some tweaks to be compatible Debian 7.0.
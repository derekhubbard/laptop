# Laptop
Laptop is a script to set up an macOS laptop for web and mobile development.

It can be run multiple times on the same machine safely. It installs, upgrades, or skips packages based on what is already installed on the machine.

This script is heavily based on the Thoughtbot version by the same name: [https://github.com/thoughtbot/laptop](https://github.com/thoughtbot/laptop).

## Install Mac OSX SDK Headers 
If running OSX 10.14, install the OSX SDK Headers manually:
```
sudo installer -pkg /Library/Developer/CommandLineTools/Packages/macOS_SDK_headers_for_macOS_10.14.pkg -target /
```

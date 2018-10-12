# Laptop
Laptop is a script to set up a Mac OSX laptop for web and mobile development.

It can be run multiple times on the same machine safely. It installs, upgrades, or skips packages based on what is already installed on the machine.

This script is heavily based on the Thoughtbot version by the same name: [https://github.com/thoughtbot/laptop](https://github.com/thoughtbot/laptop).

## Install
Download the script:
```
curl --remote-name https://raw.githubusercontent.com/derekhubbard/laptop/master/mac
```

Review the script (avoid running scripts you haven't read!):
```
less mac
```

Execute the downloaded script:
```
sh mac 2>&1 | tee ~/laptop.log
```

Optionally, review the log:
```
less ~/laptop.log
```

## Additional Installation Notes
If running OSX 10.14, install the OSX SDK Headers manually:
```
sudo installer -pkg /Library/Developer/CommandLineTools/Packages/macOS_SDK_headers_for_macOS_10.14.pkg -target /
```
## What It Sets Up
TODO

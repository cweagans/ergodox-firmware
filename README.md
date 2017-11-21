# Ergodox Firmware

This is my Ergodox Infinity firmware. I use this as my daily driver on both of my Ergodox Infinity keyboards.

## Changes

* Import MDErgo1-Default.json into the [configurator](https://input.club/configurator-ergodox/)
* Make changes (note: it's important to stay on the LTS release. Otherwise, layer toggling doesn't work right)
* Click the "Download firmware" button
* Replace files in this git repo

## Flashing

* `brew install dfu-util`
* Connect right half of the keyboard and put it in flash mode
* `dfu-util -D right_kiibohd.dfu.bin`
* Wait for keyboard to reboot
* Connect left half of keyboard and put it in flash mode
* `dfu-util -D left_kiibohd.dfu.bin`
* Wait for keyboard to reboot

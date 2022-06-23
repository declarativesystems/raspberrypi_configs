# Raspberry Pi headless setup for Raspberry Pi OS

Adjust files as needed and copy everything to the `/boot` partition on the SD card

## /boot/ssh
* enable ssh server

## /boot/userconf.txt

* Password for the `pi` user
* `ENCRYPTED_PASSWORD` from `echo 'mypassword' | openssl passwd -6 -stdin`

## /boot/wpa_supplicant.conf

* WIFI setup


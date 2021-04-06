# ox1dizer

- frontdoor for chromebooks
- in development, looks like it is working though
- might wipe your device, be careful
- requires WP disable
- can patch forced reinrollment (hopefully)
- you will need API keys

## building the exploit
- runs off recovery mode
- uses an official signed kernel image from google then offloads to custom code
- might trigger a device wipe when we swap userspace to developer mode
- you will need a linux machine and a USB drive of at least 6gb
- a fast internet connection is recommended as ox1dizer needs to download about 1gb of files
- your USB drive will be wiped

- start ox1dizer
- plug in your usb drive
- select it and press start
- follow onscreen instructions
- magic hax do everything automagically once you boot the USB

- disclaimer: this might wipe your device but will not brick it. if your device fails to boot shift click the start button to make a rootfs restore image

# Payload_Launcher
Uses the reboot to payload system to launch payloads from User Page applet.

Works on atmosphere. Should also work on sx and reinx.

![Img](screenshot.jpg)

### How to install
1. Download [this zip]() and extract the contents to `sdmc:/atmosphere`
2. Download `Payload_launcher.nro` and rename it to `reboot_to_payload.nro`
3. Move the now renamed `reboot_to_payload.nro` to `sdmc:/atmosphere/`
4. Create a folder called `payloads` on the root on the sd card and place your payload.bin files in there
5. If everything was copied and renamed correctly, you should be able to access the Payload Launcher through the User Page applet (Titled ID: `0100000000001013`)

### Misc.
You can change the applet that the Payload Launcher NRO is launched from. By changing `sdmc:/atmosphere/titles/0100000000001013` to `sdmc:/atmosphere/titles/010000000000100B`, the NRO will now be launched from the Nintendo eShop applet.  
  
You can find Nintendo Switch System Title IDs [here](https://switchbrew.org/wiki/Title_list)

### Credits

Uses part of the atmosphere code from [the atmosphere repo](https://github.com/Atmosphere-NX/Atmosphere/blob/master/troposphere/reboot_to_payload/source/main.c). Licence of the atmosphere repo is included as AMS_LICENCE.

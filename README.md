This is a fork of https://github.com/SodaqMoja/SodaqCore-samd and only extends it with a `package.json`, a `version.txt` and the [`CMSIS 4.0.0`](http://downloads.arduino.cc/CMSIS-4.0.0.tar.bz2) package in order to make it compatible with platformio. All other code is untouched and licensed under its oiginal license(s).

---

# SODAQ Core for SAMD21 CPU

This repository containts the source code and configuration files of the SODAQ Core
for Atmel's SAMD21 processor (used on the SODAQ Autonomo board).

## Installation on Arduino IDE

This core is available as a package in the Arduino IDE cores manager.
You'll first have to add our SODAQ configuration.  Start the IDE and go to
File > Preferences > Additional Boards Manager URLs.  Add the following URL
`http://downloads.sodaq.net/package_sodaq_index.json`.  You may have to restart
the IDE.

Open the "Boards Manager" (Tools -> Board -> Boards Manager) and install the
package called:

"SODAQ SAMD Boards"

## Support

There is a dedicated section of the Arduino Forum for general discussion and project assistance:

http://forum.arduino.cc/index.php?board=98.0

## Bugs or Issues

If you find a bug you can submit an issue here on github:

https://github.com/arduino/SodaqCore-samd/issues

SodaqCore-samd is a clone of ArduinoCore-samd, but we created a branch "autonomo"
to add all the specific details of the SODAQ board.

Before posting a new issue, please check if the same problem has been already reported by someone else
to avoid duplicates.

## Contributions

Contributions are always welcome. The preferred way to receive code cotribution is by submitting a 
Pull Request on github.

## License and credits

This core has been developed by Arduino LLC in collaboration with Atmel.

```
  Copyright (c) 2015 Arduino LLC.  All right reserved.

  This library is free software; you can redistribute it and/or
  modify it under the terms of the GNU Lesser General Public
  License as published by the Free Software Foundation; either
  version 2.1 of the License, or (at your option) any later version.

  This library is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
  See the GNU Lesser General Public License for more details.

  You should have received a copy of the GNU Lesser General Public
  License along with this library; if not, write to the Free Software
  Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
```

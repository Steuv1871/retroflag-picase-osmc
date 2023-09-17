# retroflag-picase for OSMC
A modification of RetroFlag safe shutdown installatation script from [crcerror](https://github.com/crcerror) adapted for OSMC (usr of `/boot/config-user.txt` instead of `/boot/config.txt`).

**Section 1**\
Installers for NesPi+, MegaPi, SuperPi cases and (since 2020/08/22) **NESPI4**
Support for OSMC

**Section 2**\
Uninstall for all systems and all cases\
This means uninstaller for NesPi+, MegaPi, SuperPi and GPi cases\
for RetroPie, RecalBox and BATOCERA

## Section 1. RetroFlag Pi-Case+ Safe Shutdown for OSMC

#### Turn switch "SAFE SHUTDOWN" on PCB to ON position.

![Safe Shutdown Switch](http://retroflag.com/images/nespi_case+/safe_shutdown.jpg "Safe Shutdown Switch")
<!---
#### **Multi Switch Shutdown**
with advanced shutdown features for more natural behaviour:
* If you press restart if emulator is currently running, then you will be kicked back to ES main menu
* If you press restart in ES main screen, ES will be restartet (no reboot!), good for quick saving metadata or internal saves.
* If you press power-off then Raspberry will shutdown

All metadata is always saved
--->

Turn switch "SAFE SHUTDOWN" on PCB to ON.

--------------------

#### Install for **OSMC:**
1. Make sure internet connected.
2. Connect through SSH
4. In the terminal, type the one-line command below (case sensitive):

**`wget -O - "https://raw.githubusercontent.com/Steuv1871/retroflag-picase-osmc/master/install.sh" | sudo bash`**

<!---
You can edit the python script and add some parameters to the script calls:
```
                  --restart will RESTART EmulationStation only
                  --kodi will startup KODI Media Center
                  --emukill to exit any running EMULATORS
                  --espid to check if EmulationStation is currently active
                  --emupid to check if an Emulator is running"

```
--->

## Section 2. Uninstallers

#### Example for OSMC
Type in the terminal, type the one-line command below (case sensitive):

**`wget -O - "https://raw.githubusercontent.com/Steuv1871/retroflag-picase-osmc/master/uninstall_all.sh" | sudo bash`**


# Better SMC
 A modpack based on popular Better Minecraft modpack

## About
Personal modpack that was initially based on the mod list of Better Minecraft. SMC is expanded to "Shahmi Minecraft". Configurations however were reset to defaults, and adjusted to my liking. The intent of this repository is to allow version management and as an interface to [Packwiz](https://github.com/packwiz/packwiz)

## Usage
### MultiMC
- Download release from the [Releases](https://github.com/TechnoSparks/Better-SMC/releases) section.
- Create a new instance in MultiMC
- Select import from zip
- Select the release zip downloaded earlier
- Launch the instance to begin downloading the mods. **If** there are download errors: (Curseforge may drop connections and I don't know why!)
  - Until no errors do:
  - Click "Continue" in the GUI
  - Kill Minecraft or close it
  - Relaunch again. If there are still remaining errors, repeat! Otherwise enjoy the game
- MultiMC will always sync to this repository on launch. If you'd like to disable this behaviour, disable "Custom commands" in the Instance's settings.

### Other launchers
**Auto update is not possible**
- Java is required to be installed and accessible in PATH
- Download `non-multimc.zip` and extract it into your Minecraft directory
- Run `!update-modpack.cmd` if on Windows or `!update-modpack.sh` if on Linux. **If** there are download errors: (Curseforge may drop connections and I don't know why!)
  - Until no errors do:
  - Click "Continue" in the GUI
  - Run the script again. If there are still remaining errors, repeat!
- The user of this modpack will need to run the script files again if want to update with this repository.

## Build
This modpack is broken for exporting in Modrinth and Curseforge formats due to the mixing of both platform sources.

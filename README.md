# Better SMC
 A modpack based on popular Better Minecraft modpack

## About
Personal modpack that was initially based on the mod list of Better Minecraft. SMC is expanded to "Shahmi Minecraft". Configurations however were reset to defaults, and adjusted to my liking. The intent of this repository is to allow version management and as an interface to [Packwiz](https://github.com/packwiz/packwiz)

## Usage
_Importable MultiMC instance zip package will be released in the releases section soon_

Requires:
- Minecraft 1.18.1
- Fabric Modloader 0.13.3
- [packwiz-installer-bootstrap](https://github.com/packwiz/packwiz-installer-bootstrap)

Understand [this documentation](https://packwiz.infra.link/tutorials/installing/packwiz-installer/#creating-a-multimc-instance-for-your-modpack), under the section "Creating a MultiMC instance for your modpack".
With such knowledge, if using MultiMC, the following would utilise this repository's modlist and configs:

```"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/TechnoSparks/Better-SMC/main/pack.toml```

If you are using an alternative launcher, then consider replacing `$INST_JAVA` with a proper string pointing to the Java binary.

## Build
This modpack is broken for exporting in modrinth and curseforge formats due to the mixing of both sources for the modlist.
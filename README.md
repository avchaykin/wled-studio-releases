# WLED Studio releases

Firmware builds of [WLED Studio](https://github.com/avchaykin/wled-studio), a fork of
[WLED](https://github.com/wled/WLED) with a new web interface (Studio), an on-device scripting
engine (Glow) and MCP support.

This repository holds only the published binaries and `manifest.json`; it is served by
GitHub Pages at https://avchaykin.github.io/wled-studio-releases/ and read by the update
check in the Studio interface (Settings → Firmware, and Devices).

| File | Contents |
|---|---|
| `manifest.json` | `latest` and a list of releases: version, date, notes, `source` (the tagged source), and one build per device type (`ESP32`: file, size, sha256) |
| `fw/wled-studio-<version>-<env>.bin` | OTA firmware image (upload via `/update` or Studio) |

WLED is licensed under the EUPL-1.2; so is this firmware. The source of every release is the
matching `vX.Y.Z` tag of [avchaykin/wled-studio](https://github.com/avchaykin/wled-studio).

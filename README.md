# smp-resource-pack
The nordtal.eu resource pack provides assets for the game in the form of characters within the range of `\uE000` to `\uF8FF`. It also has some vanilla overrides.

## Setup
Proper run configurations will be added soon. For now, using JetBrains Fleet, "Deploy Resourcepack" copies the contents of [`src/`](src/) into the specified `TARGET`. Only works on Windows. Make sure to adjust the `TARGET` variable to your needs in [`.fleet/run.json`](.fleet/run.json).

If you're not using Fleet, just find another way that works best for you to copy the [`src/`](src/) content into a folder inside your game's resource pack folder.

For building, just compress the contents of [`src/`](src/) into a ZIP file.

# Complete asset overview

## Default font
These characters are defined in [`minecraft/font/default.json`](src/assets/minecraft/font/default.json), making them availbale across the entire Minecraft client. 

### Role tags (`\uE000` - `\uE00F`)
| Char code      | File      | Char | Description |
|----------------|-----------|------|-------------|
| `\uE000`| ![source](src/assets/nordtal/textures/tags/settler.png) |  | Settler role full tag |
| `\uE001`| ![source](src/assets/nordtal/textures/tags/citizen.png) |  | Citizen role full tag |
| `\uE002`| ![source](src/assets/nordtal/textures/tags/knight.png) |  | Knight role full tag |
| `\uE003`| ![source](src/assets/nordtal/textures/tags/lord.png) |  | Lord role full tag |
| `\uE004`| ![source](src/assets/nordtal/textures/tags/a.png) |  | Admin role short tag |

### Region flags (`\uE010` - `\uE01F`)
| Char code      | File      | Char | Description |
|----------------|-----------|------|-------------|
| `\uE010`| ![source](src/assets/nordtal/textures/flags/other.png) |  | Other flag |
| `\uE011`| ![source](src/assets/nordtal/textures/flags/germany.png) |  | Germany flag |
| `\uE012`| ![source](src/assets/nordtal/textures/flags/netherlands.png) |  | Netherlands flag |
| `\uE013`| ![source](src/assets/nordtal/textures/flags/uk.png) |  | United Kingdom flag |
| `\uE014`| ![source](src/assets/nordtal/textures/flags/us.png) |  | United States flag |

### Logo assets (`\uE020` - `\uE02F`)
| Char code      | File      | Char | Description |
|----------------|-----------|------|-------------|
| `\uE020`| ![source](src/assets/nordtal/textures/assets/logo.png) |  | Nordtal long logo transparent height 24 |
| `\uE021`| ![source](src/assets/nordtal/textures/assets/logo.png) |  | Nordtal long logo transparent height 32 |

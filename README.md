# compose-rust-server
[Rust dedicated server](https://developer.valvesoftware.com/wiki/Rust_Dedicated_Server) based on [didstopia/rust-server](https://github.com/Didstopia/rust-server) image.

Contains some preinstalled & preconfigured plugins.

## Plugins
| Plugin  | Grants (default) |
| --- | --- |
| [Stack Size Controller](https://umod.org/plugins/stack-size-controller) |  |
| [Gather Manager](https://umod.org/plugins/gather-manager)  |  |
| [NTeleportation](https://umod.org/plugins/nteleportation) | `nteleportation.home`, `nteleportation.tpr` |
| [Backpacks](https://umod.org/plugins/backpacks) | `backpacks.use`, `backpacks.gui`, `backpacks.size.12` |
| [Quick Smelt](https://umod.org/plugins/quick-smelt) |  |
| [Furnace Splitter](https://umod.org/plugins/furnace-splitter) | `furnacesplitter.use` |
| [Time Of Day](https://umod.org/plugins/time-of-day) |  |
| [Magic Loot](https://umod.org/plugins/magic-loot) |  |

## Using
### Installing
Assuming you have [Docker](https://www.docker.com/) installed, have cloned this repository to `~/rust` directory and using Nano text editor
- `cd ~/rust`
- `cp .env.example .env`
- `nano .env` - configure server name, description, etc.

### Running
See docker compose [cli reference](https://docs.docker.com/compose/reference/)

### Recommendations
- Daily backup next files
    - `/.env`
    - `/data/oxide/plugins/*`
    - `/data/oxide/config/*`
    - `/data/oxide/oxide.config.json`
    - `/data/server/docker/cfg/*`

## Private
[Environment](https://drive.google.com/drive/folders/1WaCEp_BsFL3O04qAOJb3ItykPpzRw0zc?usp=drive_link)

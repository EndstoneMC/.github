![Banner](https://capsule-render.vercel.app/api?type=venom&height=200&color=gradient&text=Endstone&fontColor=0:8871e5,100:b678c4&desc=Your%20Bedrock%20Experience%20Elevated.&descAlignY=71&descSize=15&animation=fadeIn)

**Endstone** is a high-performance plugin framework for Minecraft Bedrock Dedicated Server.
Write plugins in **Python** or **C++** to customize your server, just like Bukkit/Paper does
for Java Edition.

**[Documentation](https://endstone.dev)** |
**[Discord](https://discord.gg/xxgPuc2XN9)** |
**[PyPI](https://pypi.org/project/endstone/)**

### Get Started

```bash
pip install endstone
```

Then build your first plugin with our templates:
**[Python template](https://github.com/EndstoneMC/python-example-plugin)** |
**[C++ template](https://github.com/EndstoneMC/cpp-example-plugin)**

### The Ecosystem

| Repository | What it does |
|------------|--------------|
| **[Endstone](https://github.com/EndstoneMC/endstone)** | The core framework. Plugin API, server runtime, event system. |
| **[Endweave](https://github.com/EndstoneMC/endweave)** | Protocol translation so newer clients can join older servers. Keeps your community online during Minecraft updates instead of waiting for a server update. |
| **[Plugin Templates](https://github.com/EndstoneMC/python-example-plugin)** | Ready-to-use starter templates for [Python](https://github.com/EndstoneMC/python-example-plugin) and [C++](https://github.com/EndstoneMC/cpp-example-plugin) plugins. |
| **[Pterodactyl Egg](https://github.com/EndstoneMC/pterodactyl)** | One-click deployment on Pterodactyl and Pelican hosting panels. |

### For Contributors

| Repository | Description |
|------------|-------------|
| [stubgen](https://github.com/EndstoneMC/stubgen) | Type stub generator for pybind11 modules |
| [dwarf2cpp](https://github.com/EndstoneMC/dwarf2cpp) | Generate C++ headers from DWARF debug info |
| [bedrock-dumper](https://github.com/EndstoneMC/bedrock-dumper) | Symbol offset scanner for BDS binaries |
| [bedrock-server-data](https://github.com/EndstoneMC/bedrock-server-data) | BDS version metadata and download registry |
| [remote-dev](https://github.com/EndstoneMC/remote-dev) | Docker dev environment for Endstone C++ development |
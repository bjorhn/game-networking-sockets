# game-networking-sockets

Pre-built [GameNetworkingSockets](https://github.com/ValveSoftware/GameNetworkingSockets) binaries for Windows x64 and Linux x64.

A GitHub Actions workflow builds GNS from a pinned release tag, and publishes the artifacts as a single zip under the [`latest`](../../releases/tag/latest) release. Rebuilt on every push to master.

## Package contents

```
gns/
  include/steam/         # Header files (flat C API + types)
  lib/windows-x64/       # GameNetworkingSockets.dll + .lib
  lib/linux-x64/         # libGameNetworkingSockets.so
  LICENSE                # Valve BSD 3-Clause license
```

## License

GameNetworkingSockets is developed by Valve Corporation and licensed under the [BSD 3-Clause license](https://github.com/ValveSoftware/GameNetworkingSockets/blob/master/LICENSE). See the `NOTICE` file for details.

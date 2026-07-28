# SteamTools Patterns

Published pattern data for SteamTools.

This repository contains reviewed, consumable data only:

```text
manifests/{channel}.json
symbols/{component}.json
steamclient/{dll-sha256}.toml
steamui/{dll-sha256}.toml
```

The private [SteamTools-Pattern-Lab](https://github.com/SteamToolsProject/SteamTools-Pattern-Lab)
downloads public Steam binaries, generates candidates, validates every changed
component, and opens an update pull request here. SteamTools should consume
the manifest and pattern files from this repository.

Steam DLLs, memory dumps, account data, tickets, credentials, and runner-local
paths are intentionally excluded.

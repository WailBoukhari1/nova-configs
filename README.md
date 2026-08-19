# Nova Configs

Single source for all configs (v2ray subscription links from bee plus sources, all countries):

```
https://raw.githubusercontent.com/WailBoukhari1/nova-configs/main/subscription.txt
```

## How to use in the app (Nova Tunnel / bee plus)

Open the v2ray/subscription tab -> add a subscription -> paste the URL above.
The file is refreshed automatically every time you Push from the GUI (fastest-tested-first, dead configs last).

`push/<Country>/<ISP>/` holds per-ISP datasets: `<ISP>.txt` (v2ray links), `<ISP>_b64.txt` (base64), `<ISP>_configs.json` (full backend/payload data for that ISP, one entry per ISP with all its configs).

`bee_manifest_isp.json` is the bee-format manifest with one entry per country/ISP (for future app-side use).
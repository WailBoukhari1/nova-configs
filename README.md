# Nova Configs

V2ray subscription links extracted from bee plus sources, grouped by country and ISP, plus the combined manifest.

## How to use in the app (Nova Tunnel / bee plus)

Open the v2ray/subscription tab -> add a subscription -> paste one of these raw URLs:

- Everything: `https://raw.githubusercontent.com/WailBoukhari1/nova-configs/main/subscription.txt`
- Or per country, e.g. `https://raw.githubusercontent.com/WailBoukhari1/nova-configs/main/sub/Morocco.txt`

Available countries in `sub/`: Morocco, KSA, Germany, Ethiopia, India, UK, Pakistan, Zimbabwe, Thailand (rest grouped in `Other.txt`).

`*_b64.txt` variants are the same lists base64-encoded.

`push/<Country>/<ISP>/` contains per-ISP datasets, ordered fastest-first (tested-OK configs first, dead ones last): `<ISP>.txt` (v2ray links), `<ISP>_b64.txt` (base64), `<ISP>_configs.json` (full backend/payload data). The GUI's **Push** button (with "Sync GitHub" checked) rewrites these and pushes automatically.

`bee_manifest_isp.json` is the bee-format manifest with one entry per country/ISP (for future app-side use).
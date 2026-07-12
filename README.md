# VDG_FreightForwarder_Publish

Public static release of VDG FreightForwarder (GitHub Pages).

- Built **locally** from the private repo (`make publish`) — no GitHub CI build.
- Served from `main` / root; `.nojekyll` keeps `.wasm` + `_`-prefixed files intact.
- Access is gated: Google OAuth + an LBS-issued licence bundled at publish time.
- Kill switch: disable Pages / take the repo private to cut access.

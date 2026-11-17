# Harmony Revival

**Keep Logitech Harmony remotes and hubs working after Logitech's cloud is gone.**

Logitech has stopped developing Harmony, and is shutting down the services the
remotes depend on piece by piece: Harmony Link in 2018, then the legacy desktop
software and its servers in May 2025. Harmony Revival is an open-source,
self-hosted replacement for the MyHarmony software and cloud.

| repository | what it is |
|---|---|
| [harmony-server](https://github.com/aleksgain/harmony-server) | Self-hosted backend (Python / FastAPI, Docker) that stands in for `svcs.myharmony.com` and `setup.myharmony.com` |
| [harmony-client](https://github.com/aleksgain/harmony-client) | Desktop app for Windows, macOS and Linux (Electron) that replaces MyHarmony |
| [harmony-device-db](https://github.com/aleksgain/harmony-device-db) | Packaged snapshot of the Harmony IR database: about 278,000 devices and 13 million commands |

## Help needed now: hub captures

Logitech's servers are **still online**. The protocol a hub uses to sync its
configuration (`Discovery.svc`) is undocumented, and it can only be recorded
while those servers answer. If you have a Harmony Hub and a PC, a 15-minute
capture helps more than any code.

**[Submit a hub capture →](https://github.com/aleksgain/harmony-server/issues/new?template=hub-capture.md)**

## Get involved

- Contributing: see `CONTRIBUTING.md` in each repository
- [Code of Conduct](https://github.com/aleksgain/harmony-org/blob/main/.github/CODE_OF_CONDUCT.md)
- [Security policy](https://github.com/aleksgain/harmony-org/blob/main/.github/SECURITY.md)

Harmony Revival is not affiliated with or endorsed by Logitech. "Logitech" and
"Harmony" are trademarks of Logitech.

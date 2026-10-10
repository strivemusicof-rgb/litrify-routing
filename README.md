# Litrify routing data

Weekly build of car-routing files for **Latvia, Lithuania and Estonia**, used by the
[Litrify](https://litrify.app) fuel app's trip planner.

- Built by [`.github/workflows/build.yml`](.github/workflows/build.yml) every Monday with
  [OSRM](https://project-osrm.org/) v5.27.1 (car profile, multi-level Dijkstra).
- Published as the [`latest` release](../../releases/tag/latest) (`baltics-osrm.tar.zst`).

## Data and licence
Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available under the
Open Database License (ODbL). Extracts from [Geofabrik](https://download.geofabrik.de/). The routing files
in the release are a derived database and are shared under the ODbL as well.

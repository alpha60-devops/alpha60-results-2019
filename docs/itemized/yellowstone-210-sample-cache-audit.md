---
layout: default
title: "yellowstone-210 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# yellowstone-210 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Yellowstone |
| Collection key | `yellowstone-210` |
| imdb_id | [tt4236770](https://www.imdb.com/title/tt4236770/) |
| wikipedia_url | [Yellowstone (TV series)](https://en.wikipedia.org/wiki/Yellowstone_(TV_series)) |
| Sample dates | 2019-08-29-to-2019-08-31 |
| Sample days | 3 |
| BTIH count | 45 |
| Unique BTIH count | 36 |
| Downloaders total | 175,496 |
| Uploaders total | 63,301 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-06T23:35:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190831.tar.xz
- Required sample span: 2019-08-29 to 2019-08-31 (3 days)
- Cache Day products: 3
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Yellowstone collection size histogram](figures/yellowstone-210-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/yellowstone-210-downloads-by-week-yellowstone-210-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![yellowstone-210 downloads by day](figures/yellowstone-210-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/geojson.cumulative/yellowstone-210-cumulative-aggregate.geojson.gz" data-map-title="Yellowstone — yellowstone-210" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Yellowstone (yellowstone-210) cumulative data map in new window" title="Opens interactive map for Yellowstone (yellowstone-210) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.15 | 33.49 | 15.28 | 25.97 | 4.39 | 4.92 |

### Network infrastructure

[![Yellowstone cumulative map](figures/yellowstone-210-carto.png)](figures/yellowstone-210-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/yellowstone-210-data-ge-1080p.webp)](figures/yellowstone-210-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/yellowstone-210-data-lt-1080p.webp)](figures/yellowstone-210-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

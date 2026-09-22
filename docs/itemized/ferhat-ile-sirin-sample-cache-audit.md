---
layout: default
title: "ferhat-ile-sirin Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# ferhat-ile-sirin sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Ferhat Ile Sirin |
| Collection key | `ferhat-ile-sirin` |
| imdb_id | [tt11174344](https://www.imdb.com/title/tt11174344/) |
| wikipedia_url | UNAVAILABLE — no English Wikipedia page exists |
| Sample dates | 2019-11-24-to-2020-02-08 |
| Sample days | 77 |
| BTIH count | 5 |
| Unique BTIH count | 5 |
| Downloaders total | 41,592 |
| Uploaders total | 2,564 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20200208.tar.xz
- Required sample span: 2019-11-24 to 2020-02-08 (77 days)
- Cache Day products: 77
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Ferhat Ile Sirin collection size histogram](figures/ferhat-ile-sirin-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/ferhat-ile-sirin-downloads-by-week-ferhat-ile-sirin-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![ferhat-ile-sirin downloads by day](figures/ferhat-ile-sirin-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/geojson.cumulative/ferhat-ile-sirin-cumulative-aggregate.geojson.gz" data-map-title="Ferhat Ile Sirin — ferhat-ile-sirin" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Ferhat Ile Sirin (ferhat-ile-sirin) cumulative data map in new window" title="Opens interactive map for Ferhat Ile Sirin (ferhat-ile-sirin) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.19 | 8.87 | 10.73 | 29.20 | 0.37 | 1.11 |

### Network infrastructure

[![Ferhat Ile Sirin cumulative map](figures/ferhat-ile-sirin-carto.png)](figures/ferhat-ile-sirin-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/ferhat-ile-sirin-data-ge-1080p.webp)](figures/ferhat-ile-sirin-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/ferhat-ile-sirin-data-lt-1080p.webp)](figures/ferhat-ile-sirin-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

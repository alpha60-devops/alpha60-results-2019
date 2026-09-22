---
layout: default
title: "walking-dead-1008 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# walking-dead-1008 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Walking Dead |
| Collection key | `walking-dead-1008` |
| imdb_id | [tt1520211](https://www.imdb.com/title/tt1520211/) |
| wikipedia_url | [The Walking Dead (TV series)](https://en.wikipedia.org/wiki/The_Walking_Dead_(TV_series)) |
| Sample dates | 2019-11-25-to-2020-01-12 |
| Sample days | 49 |
| BTIH count | 87 |
| Unique BTIH count | 76 |
| Downloaders total | 2,442,977 |
| Uploaders total | 846,416 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20200112.tar.xz
- Required sample span: 2019-11-25 to 2020-01-12 (49 days)
- Cache Day products: 48
- Sparse Day indices: 1
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index: 4

## 3. File sizes histogram *median[lowest, highest]*

![The Walking Dead collection size histogram](figures/walking-dead-1008-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/walking-dead-1008-downloads-by-week-walking-dead-1008-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![walking-dead-1008 downloads by day](figures/walking-dead-1008-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/geojson.cumulative/walking-dead-1008-cumulative-aggregate.geojson.gz" data-map-title="The Walking Dead — walking-dead-1008" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Walking Dead (walking-dead-1008) cumulative data map in new window" title="Opens interactive map for The Walking Dead (walking-dead-1008) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.38 | 26.30 | 15.52 | 41.86 | 2.86 | 1.15 |

### Network infrastructure

[![The Walking Dead cumulative map](figures/walking-dead-1008-carto.png)](figures/walking-dead-1008-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/walking-dead-1008-data-ge-1080p.webp)](figures/walking-dead-1008-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/walking-dead-1008-data-lt-1080p.webp)](figures/walking-dead-1008-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

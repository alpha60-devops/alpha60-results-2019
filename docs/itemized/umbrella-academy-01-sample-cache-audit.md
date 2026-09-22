---
layout: default
title: "umbrella-academy-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# umbrella-academy-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Umbrella Academy |
| Collection key | `umbrella-academy-01` |
| imdb_id | [tt1312171](https://www.imdb.com/title/tt1312171/) |
| wikipedia_url | [The Umbrella Academy (TV series)](https://en.wikipedia.org/wiki/The_Umbrella_Academy_(TV_series)) |
| Sample dates | 2019-02-15-to-2019-04-11 |
| Sample days | 56 |
| BTIH count | 243 |
| Unique BTIH count | 225 |
| Downloaders total | 4,986,564 |
| Uploaders total | 2,469,316 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190411.tar.xz
- Required sample span: 2019-02-15 to 2019-04-11 (56 days)
- Cache Day products: 56
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![The Umbrella Academy collection size histogram](figures/umbrella-academy-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/umbrella-academy-01-downloads-by-week-umbrella-academy-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![umbrella-academy-01 downloads by day](figures/umbrella-academy-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/geojson.cumulative/umbrella-academy-01-cumulative-aggregate.geojson.gz" data-map-title="The Umbrella Academy — umbrella-academy-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Umbrella Academy (umbrella-academy-01) cumulative data map in new window" title="Opens interactive map for The Umbrella Academy (umbrella-academy-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.43 | 17.89 | 31.83 | 31.89 | 2.76 | 1.07 |

### Network infrastructure

[![The Umbrella Academy cumulative map](figures/umbrella-academy-01-carto.png)](figures/umbrella-academy-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/umbrella-academy-01-data-ge-1080p.webp)](figures/umbrella-academy-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/umbrella-academy-01-data-lt-1080p.webp)](figures/umbrella-academy-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

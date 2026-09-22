---
layout: default
title: "tales-of-the-city-2019 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# tales-of-the-city-2019 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Tales of the City 2019 |
| Collection key | `tales-of-the-city-2019` |
| imdb_id | [tt7087260](https://www.imdb.com/title/tt7087260/) |
| wikipedia_url | [Tales of the City (2019 miniseries)](https://en.wikipedia.org/wiki/Tales_of_the_City_(2019_miniseries)) |
| Sample dates | 2019-06-07-to-2019-08-15 |
| Sample days | 70 |
| BTIH count | 141 |
| Unique BTIH count | 122 |
| Downloaders total | 3,677,496 |
| Uploaders total | 241,294 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190815.tar.xz
- Required sample span: 2019-06-07 to 2019-08-15 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Tales of the City 2019 collection size histogram](figures/tales-of-the-city-2019-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/tales-of-the-city-2019-downloads-by-week-tales-of-the-city-2019-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![tales-of-the-city-2019 downloads by day](figures/tales-of-the-city-2019-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/geojson.cumulative/tales-of-the-city-2019-cumulative-aggregate.geojson.gz" data-map-title="Tales of the City 2019 — tales-of-the-city-2019" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Tales of the City 2019 (tales-of-the-city-2019) cumulative data map in new window" title="Opens interactive map for Tales of the City 2019 (tales-of-the-city-2019) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.97 | 37.48 | 20.52 | 22.43 | 1.70 | 11.93 |

### Network infrastructure

[![Tales of the City 2019 cumulative map](figures/tales-of-the-city-2019-carto.png)](figures/tales-of-the-city-2019-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/tales-of-the-city-2019-data-ge-1080p.webp)](figures/tales-of-the-city-2019-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/tales-of-the-city-2019-data-lt-1080p.webp)](figures/tales-of-the-city-2019-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

---
layout: default
title: "wu-assassins-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# wu-assassins-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Wu Assassins |
| Collection key | `wu-assassins-01` |
| imdb_id | [tt8652642](https://www.imdb.com/title/tt8652642/) |
| wikipedia_url | [Wu Assassins](https://en.wikipedia.org/wiki/Wu_Assassins) |
| Sample dates | 2019-08-08-to-2019-10-16 |
| Sample days | 70 |
| BTIH count | 172 |
| Unique BTIH count | 152 |
| Downloaders total | 7,747,480 |
| Uploaders total | 909,901 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20191016.tar.xz
- Required sample span: 2019-08-08 to 2019-10-16 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Wu Assassins collection size histogram](figures/wu-assassins-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/wu-assassins-01-downloads-by-week-wu-assassins-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![wu-assassins-01 downloads by day](figures/wu-assassins-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/geojson.cumulative/wu-assassins-01-cumulative-aggregate.geojson.gz" data-map-title="Wu Assassins — wu-assassins-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Wu Assassins (wu-assassins-01) cumulative data map in new window" title="Opens interactive map for Wu Assassins (wu-assassins-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.87 | 34.38 | 23.35 | 21.81 | 1.61 | 10.68 |

### Network infrastructure

[![Wu Assassins cumulative map](figures/wu-assassins-01-carto.png)](figures/wu-assassins-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/wu-assassins-01-data-ge-1080p.webp)](figures/wu-assassins-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/wu-assassins-01-data-lt-1080p.webp)](figures/wu-assassins-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

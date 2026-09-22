---
layout: default
title: "marvelous-mrs-maisel-03 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# marvelous-mrs-maisel-03 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Marvelous Mrs. Maisel |
| Collection key | `marvelous-mrs-maisel-03` |
| imdb_id | [tt5788792](https://www.imdb.com/title/tt5788792/) |
| wikipedia_url | [The Marvelous Mrs. Maisel](https://en.wikipedia.org/wiki/The_Marvelous_Mrs._Maisel) |
| Sample dates | 2019-12-06-to-2020-02-13 |
| Sample days | 70 |
| BTIH count | 203 |
| Unique BTIH count | 193 |
| Downloaders total | 2,725,785 |
| Uploaders total | 559,622 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20200213.tar.xz
- Required sample span: 2019-12-06 to 2020-02-13 (70 days)
- Cache Day products: 69
- Sparse Day indices: 1
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index: 57

## 3. File sizes histogram *median[lowest, highest]*

![Marvelous Mrs. Maisel collection size histogram](figures/marvelous-mrs-maisel-03-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/marvelous-mrs-maisel-03-downloads-by-week-marvelous-mrs-maisel-03-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![marvelous-mrs-maisel-03 downloads by day](figures/marvelous-mrs-maisel-03-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2019/refs/heads/main/data/geojson.cumulative/marvelous-mrs-maisel-03-cumulative-aggregate.geojson.gz" data-map-title="Marvelous Mrs. Maisel — marvelous-mrs-maisel-03" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Marvelous Mrs. Maisel (marvelous-mrs-maisel-03) cumulative data map in new window" title="Opens interactive map for Marvelous Mrs. Maisel (marvelous-mrs-maisel-03) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.02 | 20.21 | 23.08 | 48.22 | 2.10 | 2.09 |

### Network infrastructure

[![Marvelous Mrs. Maisel cumulative map](figures/marvelous-mrs-maisel-03-carto.png)](figures/marvelous-mrs-maisel-03-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/marvelous-mrs-maisel-03-data-ge-1080p.webp)](figures/marvelous-mrs-maisel-03-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/marvelous-mrs-maisel-03-data-lt-1080p.webp)](figures/marvelous-mrs-maisel-03-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

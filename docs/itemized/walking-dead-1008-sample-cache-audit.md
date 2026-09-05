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

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20200112.tar.xz
- Required sample span: 2019-11-25 to 2020-01-12 (49 days)
- Cache Day products: 48
- Sparse Day indices: 1
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index: 4

## 3. Media objects file size histogram

![The Walking Dead collection size histogram](figures/walking-dead-1008-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

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

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.38 | 26.30 | 15.52 | 41.86 | 2.86 | 1.15 |

### Cumulative network infrastructure

[![The Walking Dead cumulative map](figures/walking-dead-1008-carto.png)](figures/walking-dead-1008-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/walking-dead-1008-data-ge-1080p.webp)](figures/walking-dead-1008-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/walking-dead-1008-data-lt-1080p.webp)](figures/walking-dead-1008-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

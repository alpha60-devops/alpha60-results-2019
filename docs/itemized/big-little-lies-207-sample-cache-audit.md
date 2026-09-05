---
layout: default
title: "big-little-lies-207 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# big-little-lies-207 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Big Little Lies |
| Collection key | `big-little-lies-207` |
| imdb_id | [tt3920596](https://www.imdb.com/title/tt3920596/) |
| wikipedia_url | [Big Little Lies (TV series)](https://en.wikipedia.org/wiki/Big_Little_Lies_(TV_series)) |
| Sample dates | 2019-07-22-to-2019-08-25 |
| Sample days | 35 |
| BTIH count | 90 |
| Unique BTIH count | 72 |
| Downloaders total | 1,918,313 |
| Uploaders total | 822,532 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190825.tar.xz
- Required sample span: 2019-07-22 to 2019-08-25 (35 days)
- Cache Day products: 35
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Big Little Lies collection size histogram](figures/big-little-lies-207-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/big-little-lies-207-downloads-by-week-big-little-lies-207-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![big-little-lies-207 downloads by day](figures/big-little-lies-207-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.84 | 22.05 | 14.92 | 42.36 | 4.27 | 1.72 |

### Cumulative network infrastructure

[![Big Little Lies cumulative map](figures/big-little-lies-207-carto.png)](figures/big-little-lies-207-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/big-little-lies-207-data-ge-1080p.webp)](figures/big-little-lies-207-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/big-little-lies-207-data-lt-1080p.webp)](figures/big-little-lies-207-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

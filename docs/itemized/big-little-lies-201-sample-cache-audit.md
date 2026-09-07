---
layout: default
title: "big-little-lies-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# big-little-lies-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Big Little Lies |
| Collection key | `big-little-lies-201` |
| imdb_id | [tt3920596](https://www.imdb.com/title/tt3920596/) |
| wikipedia_url | [Big Little Lies (TV series)](https://en.wikipedia.org/wiki/Big_Little_Lies_(TV_series)) |
| Sample dates | 2019-06-10-to-2019-07-21 |
| Sample days | 42 |
| BTIH count | 62 |
| Unique BTIH count | 47 |
| Downloaders total | 1,490,278 |
| Uploaders total | 686,683 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T23:35:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190721.tar.xz
- Required sample span: 2019-06-10 to 2019-07-21 (42 days)
- Cache Day products: 42
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Big Little Lies collection size histogram](figures/big-little-lies-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/big-little-lies-201-downloads-by-week-big-little-lies-201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![big-little-lies-201 downloads by day](figures/big-little-lies-201-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.75 | 24.88 | 17.08 | 35.51 | 5.36 | 1.77 |

### Cumulative network infrastructure

[![Big Little Lies cumulative map](figures/big-little-lies-201-carto.png)](figures/big-little-lies-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/big-little-lies-201-data-ge-1080p.webp)](figures/big-little-lies-201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/big-little-lies-201-data-lt-1080p.webp)](figures/big-little-lies-201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

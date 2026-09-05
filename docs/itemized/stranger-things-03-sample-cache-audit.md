---
layout: default
title: "stranger-things-03 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# stranger-things-03 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Stranger Things |
| Collection key | `stranger-things-03` |
| imdb_id | [tt4574334](https://www.imdb.com/title/tt4574334/) |
| wikipedia_url | [Stranger Things](https://en.wikipedia.org/wiki/Stranger_Things) |
| Sample dates | 2019-07-04-to-2019-09-25 |
| Sample days | 84 |
| BTIH count | 326 |
| Unique BTIH count | 283 |
| Downloaders total | 16,073,595 |
| Uploaders total | 7,289,132 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190925.tar.xz
- Required sample span: 2019-07-04 to 2019-09-25 (84 days)
- Cache Day products: 81
- Sparse Day indices: 3
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index: 26
- missing Day index: 27
- missing Day index: 28

## 3. Media objects file size histogram

![Stranger Things collection size histogram](figures/stranger-things-03-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/stranger-things-03-downloads-by-week-stranger-things-03-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![stranger-things-03 downloads by day](figures/stranger-things-03-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.16 | 18.11 | 31.45 | 33.55 | 2.12 | 1.24 |

### Cumulative network infrastructure

[![Stranger Things cumulative map](figures/stranger-things-03-carto.png)](figures/stranger-things-03-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/stranger-things-03-data-ge-1080p.webp)](figures/stranger-things-03-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/stranger-things-03-data-lt-1080p.webp)](figures/stranger-things-03-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

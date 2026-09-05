---
layout: default
title: "orville-214 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# orville-214 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Orville |
| Collection key | `orville-214` |
| imdb_id | [tt5691552](https://www.imdb.com/title/tt5691552/) |
| wikipedia_url | [The Orville](https://en.wikipedia.org/wiki/The_Orville) |
| Sample dates | 2019-04-26-to-2019-06-13 |
| Sample days | 49 |
| BTIH count | 81 |
| Unique BTIH count | 64 |
| Downloaders total | 5,681,518 |
| Uploaders total | 511,905 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190613.tar.xz
- Required sample span: 2019-04-26 to 2019-06-13 (49 days)
- Cache Day products: 49
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Orville collection size histogram](figures/orville-214-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/orville-214-downloads-by-week-orville-214-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![orville-214 downloads by day](figures/orville-214-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.76 | 38.74 | 18.77 | 22.94 | 2.19 | 11.89 |

### Cumulative network infrastructure

[![The Orville cumulative map](figures/orville-214-carto.png)](figures/orville-214-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/orville-214-data-ge-1080p.webp)](figures/orville-214-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/orville-214-data-lt-1080p.webp)](figures/orville-214-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

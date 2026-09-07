---
layout: default
title: "orville-206 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# orville-206 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Orville |
| Collection key | `orville-206` |
| imdb_id | [tt5691552](https://www.imdb.com/title/tt5691552/) |
| wikipedia_url | [The Orville](https://en.wikipedia.org/wiki/The_Orville) |
| Sample dates | 2019-02-01-to-2019-02-28 |
| Sample days | 28 |
| BTIH count | 62 |
| Unique BTIH count | 55 |
| Downloaders total | 1,899,950 |
| Uploaders total | 248,437 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T23:35:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190228.tar.xz
- Required sample span: 2019-02-01 to 2019-02-28 (28 days)
- Cache Day products: 28
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Orville collection size histogram](figures/orville-206-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/orville-206-downloads-by-week-orville-206-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![orville-206 downloads by day](figures/orville-206-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.65 | 36.57 | 17.48 | 24.71 | 2.51 | 10.36 |

### Cumulative network infrastructure

[![The Orville cumulative map](figures/orville-206-carto.png)](figures/orville-206-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/orville-206-data-ge-1080p.webp)](figures/orville-206-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/orville-206-data-lt-1080p.webp)](figures/orville-206-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

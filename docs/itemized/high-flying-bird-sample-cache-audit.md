---
layout: default
title: "high-flying-bird Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# high-flying-bird sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | High Flying Bird |
| Collection key | `high-flying-bird` |
| imdb_id | [tt8128188](https://www.imdb.com/title/tt8128188/) |
| wikipedia_url | UNAVAILABLE — no English Wikipedia page exists |
| Sample dates | 2019-02-08-to-2019-03-14 |
| Sample days | 35 |
| BTIH count | 41 |
| Unique BTIH count | 28 |
| Downloaders total | 1,079,413 |
| Uploaders total | 82,793 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190314.tar.xz
- Required sample span: 2019-02-08 to 2019-03-14 (35 days)
- Cache Day products: 35
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![High Flying Bird collection size histogram](figures/high-flying-bird-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/high-flying-bird-downloads-by-week-high-flying-bird-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![high-flying-bird downloads by day](figures/high-flying-bird-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.70 | 36.70 | 18.76 | 18.48 | 1.49 | 11.53 |

### Cumulative network infrastructure

[![High Flying Bird cumulative map](figures/high-flying-bird-carto.png)](figures/high-flying-bird-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/high-flying-bird-data-ge-1080p.webp)](figures/high-flying-bird-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/high-flying-bird-data-lt-1080p.webp)](figures/high-flying-bird-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

---
layout: default
title: "oa-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# oa-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The OA |
| Collection key | `oa-02` |
| imdb_id | [tt4635282](https://www.imdb.com/title/tt4635282/) |
| wikipedia_url | [The OA](https://en.wikipedia.org/wiki/The_OA) |
| Sample dates | 2019-03-22-to-2019-05-19 |
| Sample days | 59 |
| BTIH count | 277 |
| Unique BTIH count | 226 |
| Downloaders total | 9,967,701 |
| Uploaders total | 783,839 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190519.tar.xz
- Required sample span: 2019-03-22 to 2019-05-19 (59 days)
- Cache Day products: 59
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The OA collection size histogram](figures/oa-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/oa-02-downloads-by-week-oa-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![oa-02 downloads by day](figures/oa-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.10 | 39.22 | 20.23 | 22.21 | 1.73 | 12.28 |

### Cumulative network infrastructure

[![The OA cumulative map](figures/oa-02-carto.png)](figures/oa-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/oa-02-data-ge-1080p.webp)](figures/oa-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/oa-02-data-lt-1080p.webp)](figures/oa-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

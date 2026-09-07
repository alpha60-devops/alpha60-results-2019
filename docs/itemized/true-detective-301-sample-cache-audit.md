---
layout: default
title: "true-detective-301 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# true-detective-301 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | True Detective |
| Collection key | `true-detective-301` |
| imdb_id | [tt2356777](https://www.imdb.com/title/tt2356777/) |
| wikipedia_url | [True Detective](https://en.wikipedia.org/wiki/True_Detective) |
| Sample dates | 2019-01-14-to-2019-02-10 |
| Sample days | 28 |
| BTIH count | 132 |
| Unique BTIH count | 107 |
| Downloaders total | 2,726,570 |
| Uploaders total | 1,289,903 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T23:35:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190210.tar.xz
- Required sample span: 2019-01-14 to 2019-02-10 (28 days)
- Cache Day products: 28
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![True Detective collection size histogram](figures/true-detective-301-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/true-detective-301-downloads-by-week-true-detective-301-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![true-detective-301 downloads by day](figures/true-detective-301-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.37 | 24.39 | 15.95 | 43.81 | 4.07 | 0.93 |

### Cumulative network infrastructure

[![True Detective cumulative map](figures/true-detective-301-carto.png)](figures/true-detective-301-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/true-detective-301-data-ge-1080p.webp)](figures/true-detective-301-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/true-detective-301-data-lt-1080p.webp)](figures/true-detective-301-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

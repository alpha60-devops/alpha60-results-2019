---
layout: default
title: "succession-210 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# succession-210 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Succession |
| Collection key | `succession-210` |
| imdb_id | [tt7660850](https://www.imdb.com/title/tt7660850/) |
| wikipedia_url | [Succession (TV series)](https://en.wikipedia.org/wiki/Succession_(TV_series)) |
| Sample dates | 2019-10-14-to-2019-11-17 |
| Sample days | 35 |
| BTIH count | 67 |
| Unique BTIH count | 55 |
| Downloaders total | 576,533 |
| Uploaders total | 258,093 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T23:35:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20191117.tar.xz
- Required sample span: 2019-10-14 to 2019-11-17 (35 days)
- Cache Day products: 35
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Succession collection size histogram](figures/succession-210-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/succession-210-downloads-by-week-succession-210-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![succession-210 downloads by day](figures/succession-210-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.93 | 24.76 | 17.62 | 35.83 | 3.84 | 2.40 |

### Cumulative network infrastructure

[![Succession cumulative map](figures/succession-210-carto.png)](figures/succession-210-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/succession-210-data-ge-1080p.webp)](figures/succession-210-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/succession-210-data-lt-1080p.webp)](figures/succession-210-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

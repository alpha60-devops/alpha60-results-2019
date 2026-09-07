---
layout: default
title: "i-am-the-night-103 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# i-am-the-night-103 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | I Am The Night |
| Collection key | `i-am-the-night-103` |
| imdb_id | [tt7186588](https://www.imdb.com/title/tt7186588/) |
| wikipedia_url | [I Am the Night (TV series)](https://en.wikipedia.org/wiki/I_Am_the_Night_(TV_series)) |
| Sample dates | 2019-02-12-to-2019-03-04 |
| Sample days | 21 |
| BTIH count | 76 |
| Unique BTIH count | 61 |
| Downloaders total | 1,193,643 |
| Uploaders total | 107,964 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T23:35:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190304.tar.xz
- Required sample span: 2019-02-12 to 2019-03-04 (21 days)
- Cache Day products: 21
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![I Am The Night collection size histogram](figures/i-am-the-night-103-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/i-am-the-night-103-downloads-by-week-i-am-the-night-103-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![i-am-the-night-103 downloads by day](figures/i-am-the-night-103-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.86 | 37.93 | 18.96 | 19.96 | 1.93 | 11.53 |

### Cumulative network infrastructure

[![I Am The Night cumulative map](figures/i-am-the-night-103-carto.png)](figures/i-am-the-night-103-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/i-am-the-night-103-data-ge-1080p.webp)](figures/i-am-the-night-103-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/i-am-the-night-103-data-lt-1080p.webp)](figures/i-am-the-night-103-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

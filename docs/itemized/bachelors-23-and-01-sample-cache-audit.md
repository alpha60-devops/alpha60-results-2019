---
layout: default
title: "bachelors-23-and-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# bachelors-23-and-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Bachelors USA 23 UK 1 |
| Collection key | `bachelors-23-and-01` |
| imdb_id | [tt0313038](https://www.imdb.com/title/tt0313038/) |
| wikipedia_url | [The Bachelor (American TV series) season 23](https://en.wikipedia.org/wiki/The_Bachelor_(American_TV_series)_season_23) |
| Sample dates | 2019-03-12-to-2019-04-08 |
| Sample days | 28 |
| BTIH count | 58 |
| Unique BTIH count | 43 |
| Downloaders total | 353,810 |
| Uploaders total | 126,571 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-06T23:35:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190408.tar.xz
- Required sample span: 2019-03-12 to 2019-04-08 (28 days)
- Cache Day products: 28
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Bachelors USA 23 UK 1 collection size histogram](figures/bachelors-23-and-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/bachelors-23-and-01-downloads-by-week-bachelors-23-and-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![bachelors-23-and-01 downloads by day](figures/bachelors-23-and-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 9.63 | 30.37 | 16.25 | 22.53 | 3.03 | 5.48 |

### Cumulative network infrastructure

[![The Bachelors USA 23 UK 1 cumulative map](figures/bachelors-23-and-01-carto.png)](figures/bachelors-23-and-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/bachelors-23-and-01-data-ge-1080p.webp)](figures/bachelors-23-and-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/bachelors-23-and-01-data-lt-1080p.webp)](figures/bachelors-23-and-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

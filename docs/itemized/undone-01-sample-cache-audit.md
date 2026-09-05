---
layout: default
title: "undone-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# undone-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Undone |
| Collection key | `undone-01` |
| imdb_id | [tt8101850](https://www.imdb.com/title/tt8101850/) |
| wikipedia_url | [Undone (TV series)](https://en.wikipedia.org/wiki/Undone_(TV_series)) |
| Sample dates | 2019-09-13-to-2019-11-21 |
| Sample days | 70 |
| BTIH count | 176 |
| Unique BTIH count | 161 |
| Downloaders total | 5,286,167 |
| Uploaders total | 257,720 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20191121.tar.xz
- Required sample span: 2019-09-13 to 2019-11-21 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Undone collection size histogram](figures/undone-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/undone-01-downloads-by-week-undone-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![undone-01 downloads by day](figures/undone-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.60 | 38.53 | 20.47 | 22.06 | 1.66 | 12.60 |

### Cumulative network infrastructure

[![Undone cumulative map](figures/undone-01-carto.png)](figures/undone-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/undone-01-data-ge-1080p.webp)](figures/undone-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/undone-01-data-lt-1080p.webp)](figures/undone-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

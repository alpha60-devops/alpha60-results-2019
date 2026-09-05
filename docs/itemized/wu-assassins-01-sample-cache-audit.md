---
layout: default
title: "wu-assassins-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# wu-assassins-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Wu Assassins |
| Collection key | `wu-assassins-01` |
| imdb_id | [tt8652642](https://www.imdb.com/title/tt8652642/) |
| wikipedia_url | [Wu Assassins](https://en.wikipedia.org/wiki/Wu_Assassins) |
| Sample dates | 2019-08-08-to-2019-10-16 |
| Sample days | 70 |
| BTIH count | 172 |
| Unique BTIH count | 152 |
| Downloaders total | 7,747,480 |
| Uploaders total | 909,901 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20191016.tar.xz
- Required sample span: 2019-08-08 to 2019-10-16 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Wu Assassins collection size histogram](figures/wu-assassins-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/wu-assassins-01-downloads-by-week-wu-assassins-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![wu-assassins-01 downloads by day](figures/wu-assassins-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.87 | 34.38 | 23.35 | 21.81 | 1.61 | 10.68 |

### Cumulative network infrastructure

[![Wu Assassins cumulative map](figures/wu-assassins-01-carto.png)](figures/wu-assassins-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/wu-assassins-01-data-ge-1080p.webp)](figures/wu-assassins-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/wu-assassins-01-data-lt-1080p.webp)](figures/wu-assassins-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

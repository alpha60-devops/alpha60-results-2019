---
layout: default
title: "game-of-thrones-801 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# game-of-thrones-801 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Game of Thrones |
| Collection key | `game-of-thrones-801` |
| imdb_id | [tt0944947](https://www.imdb.com/title/tt0944947/) |
| wikipedia_url | [Game of Thrones](https://en.wikipedia.org/wiki/Game_of_Thrones) |
| Sample dates | 2019-04-15-to-2019-06-30 |
| Sample days | 77 |
| BTIH count | 211 |
| Unique BTIH count | 184 |
| Downloaders total | 29,737,387 |
| Uploaders total | 9,098,259 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190630.tar.xz
- Required sample span: 2019-04-15 to 2019-06-30 (77 days)
- Cache Day products: 77
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Game of Thrones collection size histogram](figures/game-of-thrones-801-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/game-of-thrones-801-downloads-by-week-game-of-thrones-801-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![game-of-thrones-801 downloads by day](figures/game-of-thrones-801-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.68 | 16.64 | 36.93 | 30.62 | 2.80 | 0.59 |

### Cumulative network infrastructure

[![Game of Thrones cumulative map](figures/game-of-thrones-801-carto.png)](figures/game-of-thrones-801-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/game-of-thrones-801-data-ge-1080p.webp)](figures/game-of-thrones-801-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/game-of-thrones-801-data-lt-1080p.webp)](figures/game-of-thrones-801-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

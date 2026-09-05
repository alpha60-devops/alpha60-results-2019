---
layout: default
title: "game-of-thrones-803 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# game-of-thrones-803 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Game of Thrones |
| Collection key | `game-of-thrones-803` |
| imdb_id | [tt0944947](https://www.imdb.com/title/tt0944947/) |
| wikipedia_url | [Game of Thrones](https://en.wikipedia.org/wiki/Game_of_Thrones) |
| Sample dates | 2019-04-29-to-2019-06-09 |
| Sample days | 42 |
| BTIH count | 182 |
| Unique BTIH count | 156 |
| Downloaders total | 24,515,301 |
| Uploaders total | 7,013,832 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190609.tar.xz
- Required sample span: 2019-04-29 to 2019-06-09 (42 days)
- Cache Day products: 42
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Game of Thrones collection size histogram](figures/game-of-thrones-803-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/game-of-thrones-803-downloads-by-week-game-of-thrones-803-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![game-of-thrones-803 downloads by day](figures/game-of-thrones-803-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.10 | 17.57 | 31.64 | 32.31 | 2.93 | 0.52 |

### Cumulative network infrastructure

[![Game of Thrones cumulative map](figures/game-of-thrones-803-carto.png)](figures/game-of-thrones-803-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/game-of-thrones-803-data-ge-1080p.webp)](figures/game-of-thrones-803-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/game-of-thrones-803-data-lt-1080p.webp)](figures/game-of-thrones-803-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

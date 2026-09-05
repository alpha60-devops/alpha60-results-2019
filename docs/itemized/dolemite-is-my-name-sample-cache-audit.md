---
layout: default
title: "dolemite-is-my-name Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# dolemite-is-my-name sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Dolemite Is My Name |
| Collection key | `dolemite-is-my-name` |
| imdb_id | [tt8526872](https://www.imdb.com/title/tt8526872/) |
| wikipedia_url | [Dolemite Is My Name](https://en.wikipedia.org/wiki/Dolemite_Is_My_Name) |
| Sample dates | 2019-10-25-to-2019-12-05 |
| Sample days | 42 |
| BTIH count | 77 |
| Unique BTIH count | 52 |
| Downloaders total | 4,040,718 |
| Uploaders total | 655,658 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20191205.tar.xz
- Required sample span: 2019-10-25 to 2019-12-05 (42 days)
- Cache Day products: 40
- Sparse Day indices: 2
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index: 15
- missing Day index: 16

## 3. Media objects file size histogram

![Dolemite Is My Name collection size histogram](figures/dolemite-is-my-name-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/dolemite-is-my-name-downloads-by-week-dolemite-is-my-name-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![dolemite-is-my-name downloads by day](figures/dolemite-is-my-name-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.44 | 33.90 | 18.83 | 25.31 | 1.97 | 9.16 |

### Cumulative network infrastructure

[![Dolemite Is My Name cumulative map](figures/dolemite-is-my-name-carto.png)](figures/dolemite-is-my-name-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/dolemite-is-my-name-data-ge-1080p.webp)](figures/dolemite-is-my-name-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/dolemite-is-my-name-data-lt-1080p.webp)](figures/dolemite-is-my-name-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

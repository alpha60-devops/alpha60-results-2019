---
layout: default
title: "queer-eye-2018-04 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# queer-eye-2018-04 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Queer Eye 2018 |
| Collection key | `queer-eye-2018-04` |
| imdb_id | [tt7259746](https://www.imdb.com/title/tt7259746/) |
| wikipedia_url | [Queer Eye (2018 TV series)](https://en.wikipedia.org/wiki/Queer_Eye_(2018_TV_series)) |
| Sample dates | 2019-07-19-to-2019-09-26 |
| Sample days | 70 |
| BTIH count | 91 |
| Unique BTIH count | 87 |
| Downloaders total | 2,798,123 |
| Uploaders total | 85,246 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190926.tar.xz
- Required sample span: 2019-07-19 to 2019-09-26 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Queer Eye 2018 collection size histogram](figures/queer-eye-2018-04-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/queer-eye-2018-04-downloads-by-week-queer-eye-2018-04-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![queer-eye-2018-04 downloads by day](figures/queer-eye-2018-04-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.37 | 39.13 | 19.99 | 19.76 | 1.44 | 13.30 |

### Cumulative network infrastructure

[![Queer Eye 2018 cumulative map](figures/queer-eye-2018-04-carto.png)](figures/queer-eye-2018-04-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/queer-eye-2018-04-data-ge-1080p.webp)](figures/queer-eye-2018-04-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/queer-eye-2018-04-data-lt-1080p.webp)](figures/queer-eye-2018-04-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

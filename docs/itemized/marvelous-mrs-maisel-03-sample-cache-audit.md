---
layout: default
title: "marvelous-mrs-maisel-03 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# marvelous-mrs-maisel-03 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Marvelous Mrs. Maisel |
| Collection key | `marvelous-mrs-maisel-03` |
| imdb_id | [tt5788792](https://www.imdb.com/title/tt5788792/) |
| wikipedia_url | [The Marvelous Mrs. Maisel](https://en.wikipedia.org/wiki/The_Marvelous_Mrs._Maisel) |
| Sample dates | 2019-12-06-to-2020-02-13 |
| Sample days | 70 |
| BTIH count | 203 |
| Unique BTIH count | 193 |
| Downloaders total | 2,725,785 |
| Uploaders total | 559,622 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20200213.tar.xz
- Required sample span: 2019-12-06 to 2020-02-13 (70 days)
- Cache Day products: 69
- Sparse Day indices: 1
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index: 57

## 3. Media objects file size histogram

![Marvelous Mrs. Maisel collection size histogram](figures/marvelous-mrs-maisel-03-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/marvelous-mrs-maisel-03-downloads-by-week-marvelous-mrs-maisel-03-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![marvelous-mrs-maisel-03 downloads by day](figures/marvelous-mrs-maisel-03-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.02 | 20.21 | 23.08 | 48.22 | 2.10 | 2.09 |

### Cumulative network infrastructure

[![Marvelous Mrs. Maisel cumulative map](figures/marvelous-mrs-maisel-03-carto.png)](figures/marvelous-mrs-maisel-03-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/marvelous-mrs-maisel-03-data-ge-1080p.webp)](figures/marvelous-mrs-maisel-03-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/marvelous-mrs-maisel-03-data-lt-1080p.webp)](figures/marvelous-mrs-maisel-03-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

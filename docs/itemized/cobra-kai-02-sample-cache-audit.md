---
layout: default
title: "cobra-kai-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# cobra-kai-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Cobra Kai |
| Collection key | `cobra-kai-02` |
| imdb_id | [tt7221388](https://www.imdb.com/title/tt7221388/) |
| wikipedia_url | [Cobra Kai](https://en.wikipedia.org/wiki/Cobra_Kai) |
| Sample dates | 2019-04-24-to-2019-07-16 |
| Sample days | 84 |
| BTIH count | 152 |
| Unique BTIH count | 138 |
| Downloaders total | 7,252,183 |
| Uploaders total | 937,225 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190716.tar.xz
- Required sample span: 2019-04-24 to 2019-07-16 (84 days)
- Cache Day products: 84
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Cobra Kai collection size histogram](figures/cobra-kai-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/cobra-kai-02-downloads-by-week-cobra-kai-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![cobra-kai-02 downloads by day](figures/cobra-kai-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.50 | 38.38 | 19.31 | 20.68 | 2.19 | 11.22 |

### Cumulative network infrastructure

[![Cobra Kai cumulative map](figures/cobra-kai-02-carto.png)](figures/cobra-kai-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/cobra-kai-02-data-ge-1080p.webp)](figures/cobra-kai-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/cobra-kai-02-data-lt-1080p.webp)](figures/cobra-kai-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

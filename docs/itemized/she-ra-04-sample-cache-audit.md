---
layout: default
title: "she-ra-04 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# she-ra-04 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | She-Ra Princess of Power |
| Collection key | `she-ra-04` |
| imdb_id | [tt7745956](https://www.imdb.com/title/tt7745956/) |
| wikipedia_url | [She-Ra and the Princesses of Power](https://en.wikipedia.org/wiki/She-Ra_and_the_Princesses_of_Power) |
| Sample dates | 2019-11-05-to-2019-12-16 |
| Sample days | 42 |
| BTIH count | 29 |
| Unique BTIH count | 23 |
| Downloaders total | 151,413 |
| Uploaders total | 31,654 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20191216.tar.xz
- Required sample span: 2019-11-05 to 2019-12-16 (42 days)
- Cache Day products: 42
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![She-Ra Princess of Power collection size histogram](figures/she-ra-04-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/she-ra-04-downloads-by-week-she-ra-04-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![she-ra-04 downloads by day](figures/she-ra-04-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.48 | 17.33 | 13.59 | 49.21 | 0.94 | 2.20 |

### Cumulative network infrastructure

[![She-Ra Princess of Power cumulative map](figures/she-ra-04-carto.png)](figures/she-ra-04-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/she-ra-04-data-ge-1080p.webp)](figures/she-ra-04-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/she-ra-04-data-lt-1080p.webp)](figures/she-ra-04-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

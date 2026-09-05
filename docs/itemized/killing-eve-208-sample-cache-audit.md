---
layout: default
title: "killing-eve-208 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# killing-eve-208 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Killing Eve |
| Collection key | `killing-eve-208` |
| imdb_id | [tt7016936](https://www.imdb.com/title/tt7016936/) |
| wikipedia_url | [Killing Eve](https://en.wikipedia.org/wiki/Killing_Eve) |
| Sample dates | 2019-05-27-to-2019-07-21 |
| Sample days | 56 |
| BTIH count | 105 |
| Unique BTIH count | 85 |
| Downloaders total | 1,586,541 |
| Uploaders total | 603,432 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190721.tar.xz
- Required sample span: 2019-05-27 to 2019-07-21 (56 days)
- Cache Day products: 56
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Killing Eve collection size histogram](figures/killing-eve-208-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/killing-eve-208-downloads-by-week-killing-eve-208-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![killing-eve-208 downloads by day](figures/killing-eve-208-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.72 | 23.89 | 19.55 | 39.00 | 3.69 | 2.74 |

### Cumulative network infrastructure

[![Killing Eve cumulative map](figures/killing-eve-208-carto.png)](figures/killing-eve-208-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/killing-eve-208-data-ge-1080p.webp)](figures/killing-eve-208-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/killing-eve-208-data-lt-1080p.webp)](figures/killing-eve-208-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

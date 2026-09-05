---
layout: default
title: "glow-03 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# glow-03 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | GLOW |
| Collection key | `glow-03` |
| imdb_id | [tt5770786](https://www.imdb.com/title/tt5770786/) |
| wikipedia_url | [GLOW (TV series)](https://en.wikipedia.org/wiki/GLOW_(TV_series)) |
| Sample dates | 2019-08-09-to-2019-09-12 |
| Sample days | 35 |
| BTIH count | 145 |
| Unique BTIH count | 137 |
| Downloaders total | 6,303,136 |
| Uploaders total | 169,353 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-05T07:27:37Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Selected archive: cache.20190912.tar.xz
- Required sample span: 2019-08-09 to 2019-09-12 (35 days)
- Cache Day products: 35
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![GLOW collection size histogram](figures/glow-03-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/glow-03-downloads-by-week-glow-03-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![glow-03 downloads by day](figures/glow-03-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.43 | 40.41 | 20.24 | 19.95 | 1.51 | 13.87 |

### Cumulative network infrastructure

[![GLOW cumulative map](figures/glow-03-carto.png)](figures/glow-03-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/glow-03-data-ge-1080p.webp)](figures/glow-03-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/glow-03-data-lt-1080p.webp)](figures/glow-03-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}

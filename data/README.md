# Alpha60 results: year 2019 campaign

This directory holds the in-progress year-2019 Alpha60 results dataset. The
frozen campaign inventory contains 41 media objects at SHA-256
`54809ca736ba85a62d0e43b0ce59ad74c254ae70cd86ee8d8b8c656d46e91232`.

## Campaign inputs

- `txt/year-2019-0-media-objects.txt`: canonical ordered inventory.
- `txt/year-2019-cache-aliases.tsv`: empty alias receipt; every canonical
  key maps directly to its same-named gold cache directory and member key.
- `txt/year-2019-cache-archive-overrides.json`: explicitly reviewed archive
  endpoint selections, if any.
- `txt/year-2019-cache-archive-map.json`: exact archive paths, sizes,
  SHA-256 identities, canonical sample contracts, sparse intervals, and
  byte-balanced ord/eureka ownership.

Cache archives and raw samples are immutable external campaign inputs and are
never committed to this repository. Generated data, figures, audit pages, and
the final checksum/release manifests are added only by the verified campaign
pipeline.

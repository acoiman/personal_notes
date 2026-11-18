# Remote Sensing

**Summary**: Notes on satellite and aerial Earth observation: imagery, products, foundation models, and Earth embeddings.
**Last updated**: 2026-11-18

---

- [The Technical Debt of Earth Embedding Products](https://cloudnativegeo.org/blog/2026/02/the-technical-debt-of-earth-embedding-products/): Isaac Corley (CNG blog, Feb 2026) compares Earth [[Embeddings]] products (AlphaEarth, Clay, Tessera, Major TOM, Presto, and others) on format, grid, CRS, license and storage cost. He argues that each product's custom layout adds a "distribution tax" and recommends cloud-native formats (GeoParquet, COG, Zarr), embedded CRS and provenance, and int8 quantization. See also [[Data]]. *Keywords*: earth embeddings, foundation models, GeoParquet, Zarr, cloud-native geospatial, AlphaEarth

## Related notes

- [[Agriculture]]: agribound, which delineates field boundaries from satellite imagery and embeddings.

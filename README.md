# RetailPOS-Catalog

Optional offline barcode catalog for RetailPOS, derived from [Open Food Facts](https://world.openfoodfacts.org/) and focused on products reported as sold in Türkiye.

This repository distributes public reference data only. It contains no RetailPOS application source code, retailer prices, inventory, transactions, customer data, backups, or private signing keys.

## Data and licensing

The catalog is derived from the [Open Food Facts data exports](https://world.openfoodfacts.org/data). Credit goes to Open Food Facts and its contributors.

The derived database is licensed under the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Rights in the individual contents are licensed under the [Database Contents License (DbCL) 1.0](https://opendatacommons.org/licenses/dbcl/1-0/). See also [Open Food Facts licensing guidance](https://openfoodfacts.github.io/documentation/docs/Product-Opener/api/tutorials/license-be-on-the-legal-side/).

The catalog uses product barcodes, names, and, when available, brands, pack sizes, and modification timestamps. Images are not included. The data is community-maintained and may be incomplete or inaccurate. Türkiye country tags describe reported sales markets, not necessarily the manufacturing country. The catalog does not claim comprehensive coverage of the Turkish market.

## Distribution

Release assets include the machine-readable GZIP-compressed JSON Lines catalog, its signed manifest, and attribution/licensing notice. The signature is for authenticity and integrity verification; it does not restrict reuse under the data licenses.

The [initial v1 release](https://github.com/aliegefaki/RetailPOS-Catalog/releases/tag/v1) contains 9,094 unique valid product records (239,161 compressed bytes). Download the [latest manifest](https://github.com/aliegefaki/RetailPOS-Catalog/releases/latest/download/manifest.json) and the matching catalog asset from the same release. The recorded SHA-256 of the v1 catalog is `a7fff8c8ea151f5d20e130302b171891a763309f25a227b447525162096ed8dd`. This is a count of filtered records, not a market coverage percentage.

RetailPOS stores this optional public dataset separately from each retailer's private local database. Installation, updates, and removal do not change retailer records.

# RetailPOS-Catalog

Optional offline barcode catalog for RetailPOS, derived from [Open Food Facts](https://world.openfoodfacts.org/) and focused on products reported as sold in Türkiye.

This repository distributes public reference data only. It contains no RetailPOS application source code, retailer prices, inventory, transactions, customer data, backups, or private signing keys.

## Data and licensing

The catalog is derived from the [Open Food Facts data exports](https://world.openfoodfacts.org/data). Credit goes to Open Food Facts and its contributors.

The derived database is licensed under the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Rights in the individual contents are licensed under the [Database Contents License (DbCL) 1.0](https://opendatacommons.org/licenses/dbcl/1-0/). See also [Open Food Facts licensing guidance](https://openfoodfacts.github.io/documentation/docs/Product-Opener/api/tutorials/license-be-on-the-legal-side/).

The catalog uses product barcodes, names, and, when available, brands, pack sizes, and modification timestamps. Images are not included. The data is community-maintained and may be incomplete or inaccurate. Türkiye country tags describe reported sales markets, not necessarily the manufacturing country. The catalog does not claim comprehensive coverage of the Turkish market.

## Distribution

Release assets will include the machine-readable GZIP-compressed JSON Lines catalog and its signed manifest. The signature is for authenticity and integrity verification; it does not restrict reuse under the data licenses.

No release has been published yet.

RetailPOS stores this optional public dataset separately from each retailer's private local database. Installation, updates, and removal do not change retailer records.

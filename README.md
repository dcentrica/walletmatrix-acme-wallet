# WalletMatrix

This repo comprises an example `matrix.json` file based on the [WalletMatrix Version 3 Schema](https://walletmatrix.app/schema/v3.json). You can refer to it when maintaining your own matrix.json file.

This example is based on a fake mobile wallet app that has a comprehensive set of Security, Privacy and Lightning features. Not all features make sense together, but given the range of possible feature combinations, WalletMatrix will only validate against valid JSON and valid data with respect to the schema.

# Notes

Values are either JSON arrays of strings or of other objects, or single character strings that indicate the presence or status of a particular feature:

**Y** The feature is present
**N** The feature is not present
**P** The feature is planned for a future release
**?** The feature's status is unknown

Please refer to the schema for valid values.

Please also refer to the [glossary](https://walletmatrix.app/glossary) where matrix.json features are detailed.

# Need Help?

* [Notes and FAQ for vendors](https://walletmatrix.app/vendors)
* Contact: info@dcentrica.com or tweet us [@walletmatrix](https://twitter.com/walletmatrix)


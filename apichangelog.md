## API Change Logs
This document provides information about new features and bug fixes with the Lightroom APIs.

### Version 1.1.0 (11 Jan, 2021)
- Added new [Create Asset API](https://www.stage.adobe.io/apis/creativecloud/lightroom/apidocs.html#/assets/createAsset) - `/v2/catalogs/{catalog_id}/assets/{asset_id}` . It can be used to create a new asset with initial metadata and import information.

- Existing Create Asset Revision API - `/v2/catalogs/{catalog_id}/assets/{asset_id}/revisions/{revision_id}` is removed and will be deprecated soon. Please use above mentioned [Create Asset API](https://www.stage.adobe.io/apis/creativecloud/lightroom/apidocs.html) instead for creating asset.
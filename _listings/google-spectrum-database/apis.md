---
name: Google Spectrum Database
x-slug: google-spectrum-database
description: The Google Spectrum Database API provides PAWS-compatible JSON-RPC methods
  that allow devices to query the database to find available TV-band spectrum at a
  given geolocation.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: Google Spectrum Database
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/apis.md
specificationVersion: "0.14"
apis:
- name: Google Spectrum Database API Get Spectrum
  x-api-slug: google-spectrum-database-api
  description: Requests information about the available spectrum for a device at a
    location. Requests from a fixed-mode device must include owner information so
    the device can be registered with the database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws//getSpectrum
  tags: Spectrum
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/getspectrum-post-openapi.md
- name: Google Spectrum Database API Get Spectrum Batch
  x-api-slug: google-spectrum-database-api
  description: The Google Spectrum Database does not support batch requests, so this
    method always yields an UNIMPLEMENTED error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws//getSpectrumBatch
  tags: Spectrum
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/getspectrumbatch-post-openapi.md
- name: Google Spectrum Database API Initialize Connection
  x-api-slug: google-spectrum-database-api
  description: Initializes the connection between a white space device and the database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws//init
  tags: Connection
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/init-post-openapi.md
- name: Google Spectrum Database API Notify Spectrum Use
  x-api-slug: google-spectrum-database-api
  description: Notifies the database that the device has selected certain frequency
    ranges for transmission. Only to be invoked when required by the regulator. The
    Google Spectrum Database does not operate in domains that require notification,
    so this always yields an UNIMPLEMENTED error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws//notifySpectrumUse
  tags: Spectrum
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/notifyspectrumuse-post-openapi.md
- name: Google Spectrum Database API Register Spectrum
  x-api-slug: google-spectrum-database-api
  description: The Google Spectrum Database implements registration in the getSpectrum
    method. As such this always returns an UNIMPLEMENTED error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws//register
  tags: Spectrum
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/register-post-openapi.md
- name: Google Spectrum Database API Verify Device
  x-api-slug: google-spectrum-database-api
  description: Validates a device for white space use in accordance with regulatory
    rules. The Google Spectrum Database does not support master/slave configurations,
    so this always yields an UNIMPLEMENTED error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws//verifyDevice
  tags: Device
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/verifydevice-post-openapi.md
- name: Google Spectrum Database API
  x-api-slug: google-spectrum-database-api
  description: The Google Spectrum Database API provides PAWS-compatible JSON-RPC
    methods that allow devices to query the database to find available TV-band spectrum
    at a given geolocation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws
  tags: Google Spectrum Database
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/openapi.md
x-common:
- type: x-documentation
  url: https://developers.google.com/spectrum/v1
- type: x-getting-started
  url: https://developers.google.com/spectrum/paws/gettingstarted
- type: x-terms-of-service
  url: https://developers.google.com/spectrum/terms
- type: x-developer
  url: https://developers.google.com/spectrum/
- type: x-website
  url: https://www.google.com/get/spectrumdatabase/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
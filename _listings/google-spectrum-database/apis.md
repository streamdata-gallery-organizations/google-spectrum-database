---
name: Google Spectrum Database
x-slug: google-spectrum-database
description: The Google Spectrum Database API provides PAWS-compatible JSON-RPC methods
  that allow devices to query the database to find available TV-band spectrum at a
  given geolocation.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Spectrum Database
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/apis.md
specificationVersion: "0.14"
apis:
- name: Google Spectrum Database - Get Spectrum
  x-api-slug: getspectrum-post
  description: Requests information about the available spectrum for a device at a
    location. Requests from a fixed-mode device must include owner information so
    the device can be registered with the database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws
  tags: Spectrum, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/getspectrum-post-openapi.md
- name: Google Spectrum Database - Get Spectrum Batch
  x-api-slug: getspectrumbatch-post
  description: The Google Spectrum Database does not support batch requests, so this
    method always yields an UNIMPLEMENTED error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws
  tags: Spectrum, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/getspectrumbatch-post-openapi.md
- name: Google Spectrum Database - Initialize Connection
  x-api-slug: init-post
  description: Initializes the connection between a white space device and the database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws
  tags: Spectrum, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/init-post-openapi.md
- name: Google Spectrum Database - Notify Spectrum Use
  x-api-slug: notifyspectrumuse-post
  description: Notifies the database that the device has selected certain frequency
    ranges for transmission. Only to be invoked when required by the regulator. The
    Google Spectrum Database does not operate in domains that require notification,
    so this always yields an UNIMPLEMENTED error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws
  tags: Spectrum, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/notifyspectrumuse-post-openapi.md
- name: Google Spectrum Database - Register Spectrum
  x-api-slug: register-post
  description: The Google Spectrum Database implements registration in the getSpectrum
    method. As such this always returns an UNIMPLEMENTED error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws
  tags: Spectrum, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/register-post-openapi.md
- name: Google Spectrum Database - Verify Device
  x-api-slug: verifydevice-post
  description: Validates a device for white space use in accordance with regulatory
    rules. The Google Spectrum Database does not support master/slave configurations,
    so this always yields an UNIMPLEMENTED error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-spectrum-database-earth.jpg
  humanURL: https://www.google.com/get/spectrumdatabase/
  baseURL: ://www.googleapis.com//spectrum/v1explorer/paws
  tags: Spectrum, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-spectrum-database/master/_listings/google-spectrum-database/verifydevice-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.slides.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.spectrum.database.stack.network
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
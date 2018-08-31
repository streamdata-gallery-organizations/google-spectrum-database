---
swagger: "2.0"
x-collection-name: Google Spectrum Database
x-complete: 0
info:
  title: Google Spectrum Database API Get Spectrum
  description: Requests information about the available spectrum for a device at a
    location. Requests from a fixed-mode device must include owner information so
    the device can be registered with the database.
  contact:
    name: Google
    url: https://google.com
  version: v1explorer
host: www.googleapis.com
basePath: /spectrum/v1explorer/paws
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /getSpectrum:
    post:
      summary: Get Spectrum
      description: Requests information about the available spectrum for a device
        at a location. Requests from a fixed-mode device must include owner information
        so the device can be registered with the database.
      operationId: spectrum.paws.getSpectrum
      x-api-path-slug: getspectrum-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Spectrum
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
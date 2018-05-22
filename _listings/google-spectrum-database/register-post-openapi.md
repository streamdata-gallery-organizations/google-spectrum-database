---
swagger: "2.0"
x-collection-name: Google Spectrum Database
x-complete: 0
info:
  title: Google Spectrum Database API Register Spectrum
  description: The Google Spectrum Database implements registration in the getSpectrum
    method. As such this always returns an UNIMPLEMENTED error.
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
  /getSpectrumBatch:
    post:
      summary: Get Spectrum Batch
      description: The Google Spectrum Database does not support batch requests, so
        this method always yields an UNIMPLEMENTED error.
      operationId: spectrum.paws.getSpectrumBatch
      x-api-path-slug: getspectrumbatch-post
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
  /init:
    post:
      summary: Initialize Connection
      description: Initializes the connection between a white space device and the
        database.
      operationId: spectrum.paws.init
      x-api-path-slug: init-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Connection
  /notifySpectrumUse:
    post:
      summary: Notify Spectrum Use
      description: Notifies the database that the device has selected certain frequency
        ranges for transmission. Only to be invoked when required by the regulator.
        The Google Spectrum Database does not operate in domains that require notification,
        so this always yields an UNIMPLEMENTED error.
      operationId: spectrum.paws.notifySpectrumUse
      x-api-path-slug: notifyspectrumuse-post
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
  /register:
    post:
      summary: Register Spectrum
      description: The Google Spectrum Database implements registration in the getSpectrum
        method. As such this always returns an UNIMPLEMENTED error.
      operationId: spectrum.paws.register
      x-api-path-slug: register-post
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
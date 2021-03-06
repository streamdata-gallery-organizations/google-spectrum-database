---
swagger: "2.0"
info:
  title: Google Spectrum Database
  description: API for spectrum-management functions.
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
        at a location
      operationId: spectrum.paws.getSpectrum
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - spectrum
definitions:
  AntennaCharacteristics:
    properties:
      height:
        description: This is a default description.
        type: post
      heightType:
        description: This is a default description.
        type: post
      heightUncertainty:
        description: This is a default description.
        type: post
  DatabaseSpec:
    properties:
      name:
        description: This is a default description.
        type: post
      uri:
        description: This is a default description.
        type: post
  DbUpdateSpec:
    properties:
      databases:
        description: This is a default description.
        type: post
  DeviceCapabilities:
    properties:
      frequencyRanges:
        description: This is a default description.
        type: post
  DeviceDescriptor:
    properties:
      etsiEnDeviceCategory:
        description: This is a default description.
        type: post
      etsiEnDeviceEmissionsClass:
        description: This is a default description.
        type: post
      etsiEnDeviceType:
        description: This is a default description.
        type: post
      etsiEnTechnologyId:
        description: This is a default description.
        type: post
      fccId:
        description: This is a default description.
        type: post
      fccTvbdDeviceType:
        description: This is a default description.
        type: post
      manufacturerId:
        description: This is a default description.
        type: post
      modelId:
        description: This is a default description.
        type: post
      rulesetIds:
        description: This is a default description.
        type: post
      serialNumber:
        description: This is a default description.
        type: post
  DeviceOwner:
    properties: []
  DeviceValidity:
    properties:
      isValid:
        description: This is a default description.
        type: post
      reason:
        description: This is a default description.
        type: post
  EventTime:
    properties:
      startTime:
        description: This is a default description.
        type: post
      stopTime:
        description: This is a default description.
        type: post
  FrequencyRange:
    properties:
      channelId:
        description: This is a default description.
        type: post
      maxPowerDBm:
        description: This is a default description.
        type: post
      startHz:
        description: This is a default description.
        type: post
      stopHz:
        description: This is a default description.
        type: post
  GeoLocation:
    properties:
      confidence:
        description: This is a default description.
        type: post
  GeoLocationEllipse:
    properties:
      orientation:
        description: This is a default description.
        type: post
      semiMajorAxis:
        description: This is a default description.
        type: post
      semiMinorAxis:
        description: This is a default description.
        type: post
  GeoLocationPoint:
    properties:
      latitude:
        description: This is a default description.
        type: post
      longitude:
        description: This is a default description.
        type: post
  GeoLocationPolygon:
    properties:
      exterior:
        description: This is a default description.
        type: post
  GeoSpectrumSchedule:
    properties:
      spectrumSchedules:
        description: This is a default description.
        type: post
  PawsGetSpectrumBatchRequest:
    properties:
      locations:
        description: This is a default description.
        type: post
      requestType:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsGetSpectrumBatchResponse:
    properties:
      geoSpectrumSchedules:
        description: This is a default description.
        type: post
      kind:
        description: This is a default description.
        type: post
      maxContiguousBwHz:
        description: This is a default description.
        type: post
      maxTotalBwHz:
        description: This is a default description.
        type: post
      needsSpectrumReport:
        description: This is a default description.
        type: post
      timestamp:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsGetSpectrumRequest:
    properties:
      requestType:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsGetSpectrumResponse:
    properties:
      kind:
        description: This is a default description.
        type: post
      maxContiguousBwHz:
        description: This is a default description.
        type: post
      maxTotalBwHz:
        description: This is a default description.
        type: post
      needsSpectrumReport:
        description: This is a default description.
        type: post
      spectrumSchedules:
        description: This is a default description.
        type: post
      timestamp:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsInitRequest:
    properties:
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsInitResponse:
    properties:
      kind:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsNotifySpectrumUseRequest:
    properties:
      spectra:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsNotifySpectrumUseResponse:
    properties:
      kind:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsRegisterRequest:
    properties:
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsRegisterResponse:
    properties:
      kind:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsVerifyDeviceRequest:
    properties:
      deviceDescs:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  PawsVerifyDeviceResponse:
    properties:
      deviceValidities:
        description: This is a default description.
        type: post
      kind:
        description: This is a default description.
        type: post
      type:
        description: This is a default description.
        type: post
      version:
        description: This is a default description.
        type: post
  RulesetInfo:
    properties:
      authority:
        description: This is a default description.
        type: post
      maxLocationChange:
        description: This is a default description.
        type: post
      maxPollingSecs:
        description: This is a default description.
        type: post
      rulesetIds:
        description: This is a default description.
        type: post
  SpectrumMessage:
    properties:
      bandwidth:
        description: This is a default description.
        type: post
      frequencyRanges:
        description: This is a default description.
        type: post
  SpectrumSchedule:
    properties:
      spectra:
        description: This is a default description.
        type: post
  Vcard:
    properties:
      fn:
        description: This is a default description.
        type: post
  VcardAddress:
    properties:
      code:
        description: This is a default description.
        type: post
      country:
        description: This is a default description.
        type: post
      locality:
        description: This is a default description.
        type: post
      pobox:
        description: This is a default description.
        type: post
      region:
        description: This is a default description.
        type: post
      street:
        description: This is a default description.
        type: post
  VcardTelephone:
    properties:
      uri:
        description: This is a default description.
        type: post
  VcardTypedText:
    properties:
      text:
        description: This is a default description.
        type: post
x-collection-name: Google Spectrum Database
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
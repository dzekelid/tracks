---
swagger: "2.0"
x-collection-name: Clarify
x-complete: 0
info:
  title: Clarify Delete bundle tracks
  description: Delete tracks of a bundle. This will only delete media stored on Clarify
    systems and not delete the source media on remote systems.Successful response
    will be a HTTP code 204 with an empty body.
  version: 1.3.4
host: api.clarify.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/bundles/{bundle_id}/tracks:
    delete:
      summary: Delete bundle tracks
      description: Delete tracks of a bundle. This will only delete media stored on
        Clarify systems and not delete the source media on remote systems.Successful
        response will be a HTTP code 204 with an empty body.
      operationId: deleteV1BundlesBundleTracks
      x-api-path-slug: v1bundlesbundle-idtracks-delete
      parameters:
      - in: path
        name: bundle_id
        description: id of a bundle
      responses:
        200:
          description: OK
      tags:
      - Bundle
      - Tracks
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
---
swagger: "2.0"
x-collection-name: 7digital
x-complete: 0
info:
  title: 7digital Purchasing API playlists/{playlistId}/tracks/{playlisttrackid}
  description: Removes the specified track {playlisttrackid} from the specified playlist
    at {playlistId}.  Tracks can only be removed by the playlist owner, i.e. oauth_token
    representing the user has to be provided.
  version: "1.2"
host: api.7digital.com
basePath: 1.2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  playlists/{playlistId}/tracks/{playlisttrackid}:
    'delete ':
      summary: playlists/{playlistId}/tracks/{playlisttrackid}
      description: Removes the specified track {playlisttrackid} from the specified
        playlist at {playlistId}.  Tracks can only be removed by the playlist owner,
        i.e. oauth_token representing the user has to be provided.
      operationId: playlistsplaylistidtracksplaylisttrackid
      x-api-path-slug: playlistsplaylistidtracksplaylisttrackid-delete
      parameters:
      - ~
      - in: query
        name: oauth_token
        description: Users OAuth access token
      responses:
        200:
          description: OK
      tags:
      - Playlists
      - Tracks
      - Playlisttrackid
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
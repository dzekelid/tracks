---
swagger: "2.0"
x-collection-name: 7digital
x-complete: 1
info:
  title: 7digital Purchasing API
  description: the-purchasing-api-allows-3rd-parties-to-deliver-digital-content-to-individual-users-
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
---
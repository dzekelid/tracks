---
swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 0
info:
  title: Sound Cloud Put Tracks Track Secret Token. Format
  description: |-
    Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on
                        the server and returned. This resource can only be used by the track owner.
  version: 1.0.0
host: api.soundcloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tracks.json:
    get:
      summary: Get Tracks
      description: Returns a collection of tracks
      operationId: getTracks.json
      x-api-path-slug: tracks-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Tracks
    post:
      summary: Post Tracks
      description: Uploads a track
      operationId: postTracks.json
      x-api-path-slug: tracks-json-post
      responses:
        200:
          description: OK
      tags:
      - Tracks
  /tracks/{track_id}.json:
    get:
      summary: Get Tracks Track
      description: Returns a track by track id
      operationId: getTracksTrack.json
      x-api-path-slug: trackstrack-id-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
    put:
      summary: Put Tracks Track
      description: Updates a given track
      operationId: putTracksTrack.json
      x-api-path-slug: trackstrack-id-json-put
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
    delete:
      summary: Delete Tracks Track
      description: Deletes a given track
      operationId: deleteTracksTrack.json
      x-api-path-slug: trackstrack-id-json-delete
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
  /tracks/{track_id}/comments.json:
    get:
      summary: Get Tracks Track Comments
      description: Returns comments of a track by track id
      operationId: getTracksTrackComments.json
      x-api-path-slug: trackstrack-idcomments-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Comments
    post:
      summary: Post Tracks Track Comments
      description: Posts a comments to a track by track id
      operationId: postTracksTrackComments.json
      x-api-path-slug: trackstrack-idcomments-json-post
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Comments
  /tracks/{track_id}/permissions.json:
    get:
      summary: Get Tracks Track Permissions
      description: Returns all users with permission for a track by track id
      operationId: getTracksTrackPermissions.json
      x-api-path-slug: trackstrack-idpermissions-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Permissions
    put:
      summary: Put Tracks Track Permissions
      description: Updates the list of permitted users for a track by track id
      operationId: putTracksTrackPermissions.json
      x-api-path-slug: trackstrack-idpermissions-json-put
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Permissions
  /tracks/{track_id}/secret-token.json:
    get:
      summary: Get Tracks Track Secret Token
      description: Returns the secret token for a track by track id. This resource
        can only be used by the track owner.
      operationId: getTracksTrackSecretToken.json
      x-api-path-slug: trackstrack-idsecrettoken-json-get
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Secret
      - Token
    put:
      summary: Put Tracks Track Secret Token
      description: |-
        Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on
                  the server and returned. This resource can only be used by the track owner.
      operationId: putTracksTrackSecretToken.json
      x-api-path-slug: trackstrack-idsecrettoken-json-put
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Secret
      - Token
  /users/{user_id}/tracks.json:
    get:
      summary: Get Users Tracks
      description: Returns a collection of tracks uploaded by user id
      operationId: getUsersUserTracks.json
      x-api-path-slug: usersuser-idtracks-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Users
      - Tracks
  /me/tracks.json:
    get:
      summary: Get Me Tracks
      description: Returns a collection of tracks uploaded by logged-in user
      operationId: getMeTracks.json
      x-api-path-slug: metracks-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Tracks
  /groups/{group_id}/tracks.json:
    get:
      summary: Get Groups Tracks
      description: Returns a collection of tracks contributed to the group with group
        id
      operationId: getGroupsGroupTracks.json
      x-api-path-slug: groupsgroup-idtracks-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Tracks
  /tracks.{format}:
    get:
      summary: Get Tracks. Format
      description: Returns a collection of tracks
      operationId: getTracks.Format
      x-api-path-slug: tracks-format-get
      parameters:
      - in: query
        name: bpm-from
        description: Access, host, upload, and comment on audio
      - in: query
        name: bpm-to
        description: Access, host, upload, and comment on audio
      - in: query
        name: consumer_key
        description: Access, host, upload, and comment on audio
      - in: query
        name: created_at-from
        description: Access, host, upload, and comment on audio
      - in: query
        name: created_at-to
        description: Access, host, upload, and comment on audio
      - in: query
        name: duration-from
        description: Access, host, upload, and comment on audio
      - in: query
        name: duration-to
        description: Access, host, upload, and comment on audio
      - in: query
        name: filter
        description: Access, host, upload, and comment on audio
      - in: query
        name: ids
        description: Access, host, upload, and comment on audio
      - in: query
        name: order
        description: Access, host, upload, and comment on audio
      - in: query
        name: q
        description: Access, host, upload, and comment on audio
      - in: query
        name: tags
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - ""
      - Format
    post:
      summary: Post Tracks. Format
      description: Post tracks. format.
      operationId: postTracks.Format
      x-api-path-slug: tracks-format-post
      parameters:
      - in: query
        name: asset_data
        description: Access, host, upload, and comment on audio
      - in: query
        name: title
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - ""
      - Format
  /tracks/{track_id}.{format}:
    get:
      summary: Get Tracks Track . Format
      description: Returns a track by track id
      operationId: getTracksTrack.Format
      x-api-path-slug: trackstrack-id-format-get
      parameters:
      - in: query
        name: consumer_key
        description: Access, host, upload, and comment on audio
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - ""
      - ""
      - Format
    put:
      summary: Put Tracks Track . Format
      description: Put tracks track . format.
      operationId: putTracksTrack.Format
      x-api-path-slug: trackstrack-id-format-put
      parameters:
      - in: query
        name: asset_data
        description: Access, host, upload, and comment on audio
      - in: query
        name: title
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - ""
      - ""
      - Format
    delete:
      summary: Delete Tracks Track . Format
      description: Delete tracks track . format.
      operationId: deleteTracksTrack.Format
      x-api-path-slug: trackstrack-id-format-delete
      parameters:
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - ""
      - ""
      - Format
  /tracks/{track_id}/comments.{format}:
    get:
      summary: Get Tracks Track Comments. Format
      description: Returns comments of a track by track id
      operationId: getTracksTrackComments.Format
      x-api-path-slug: trackstrack-idcomments-format-get
      parameters:
      - in: query
        name: consumer_key
        description: Access, host, upload, and comment on audio
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Comments
      - ""
      - Format
    post:
      summary: Post Tracks Track Comments. Format
      description: Posts a comments to a track by track id
      operationId: postTracksTrackComments.Format
      x-api-path-slug: trackstrack-idcomments-format-post
      parameters:
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Comments
      - ""
      - Format
  /tracks/{track_id}/permissions.{format}:
    get:
      summary: Get Tracks Track Permissions. Format
      description: Returns all users with permission for a track by track id
      operationId: getTracksTrackPermissions.Format
      x-api-path-slug: trackstrack-idpermissions-format-get
      parameters:
      - in: query
        name: consumer_key
        description: Access, host, upload, and comment on audio
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Permissions
      - ""
      - Format
    put:
      summary: Put Tracks Track Permissions. Format
      description: Updates the list of permitted users for a track by track id
      operationId: putTracksTrackPermissions.Format
      x-api-path-slug: trackstrack-idpermissions-format-put
      parameters:
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Permissions
      - ""
      - Format
  /tracks/{track_id}/secret-token.{format}:
    get:
      summary: Get Tracks Track Secret Token. Format
      description: Returns the secret token for a track by track id. This resource
        can only be used by the track owner.
      operationId: getTracksTrackSecretToken.Format
      x-api-path-slug: trackstrack-idsecrettoken-format-get
      parameters:
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Secret
      - Token
      - ""
      - Format
    put:
      summary: Put Tracks Track Secret Token. Format
      description: |-
        Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on
                            the server and returned. This resource can only be used by the track owner.
      operationId: putTracksTrackSecretToken.Format
      x-api-path-slug: trackstrack-idsecrettoken-format-put
      parameters:
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Secret
      - Token
      - ""
      - Format
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
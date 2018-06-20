---
name: SoundCloud
x-slug: soundcloud
description: SoundCloud is a music and podcast streaming platform that lets you listen
  to millions of songs from around the world, or upload your own. Start listening
  now!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
x-kinRank: "9"
x-alexaRank: "114"
tags: Tracks
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/apis.md
specificationVersion: "0.14"
apis:
- name: Sound Cloud Get Tracks
  x-api-slug: sound-cloud
  description: Returns a collection of tracks
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks.json
  tags: Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/tracks-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/tracks-json-get-openapi.md
- name: Sound Cloud Post Tracks
  x-api-slug: sound-cloud
  description: Uploads a track
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks.json
  tags: Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/tracks-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/tracks-json-post-openapi.md
- name: Sound Cloud Get Tracks Track
  x-api-slug: sound-cloud
  description: Returns a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.json
  tags: Tracks,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-json-get-openapi.md
- name: Sound Cloud Put Tracks Track
  x-api-slug: sound-cloud
  description: Updates a given track
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.json
  tags: Tracks,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-json-put-openapi.md
- name: Sound Cloud Delete Tracks Track
  x-api-slug: sound-cloud
  description: Deletes a given track
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.json
  tags: Tracks,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-json-delete-openapi.md
- name: Sound Cloud Get Tracks Track Comments
  x-api-slug: sound-cloud
  description: Returns comments of a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.json
  tags: Tracks,Track,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idcomments-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idcomments-json-get-openapi.md
- name: Sound Cloud Post Tracks Track Comments
  x-api-slug: sound-cloud
  description: Posts a comments to a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.json
  tags: Tracks,Track,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idcomments-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idcomments-json-post-openapi.md
- name: Sound Cloud Get Tracks Track Permissions
  x-api-slug: sound-cloud
  description: Returns all users with permission for a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/permissions.json
  tags: Tracks,Track,Permissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idpermissions-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idpermissions-json-get-openapi.md
- name: Sound Cloud Put Tracks Track Permissions
  x-api-slug: sound-cloud
  description: Updates the list of permitted users for a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/permissions.json
  tags: Tracks,Track,Permissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idpermissions-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idpermissions-json-put-openapi.md
- name: Sound Cloud Get Tracks Track Secret Token
  x-api-slug: sound-cloud
  description: Returns the secret token for a track by track id. This resource can
    only be used by the track owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/secret-token.json
  tags: Tracks,Track,Secret,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idsecrettoken-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idsecrettoken-json-get-openapi.md
- name: Sound Cloud Put Tracks Track Secret Token
  x-api-slug: sound-cloud
  description: |-
    Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on
              the server and returned. This resource can only be used by the track owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/secret-token.json
  tags: Tracks,Track,Secret,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idsecrettoken-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idsecrettoken-json-put-openapi.md
- name: Sound Cloud Get Users Tracks
  x-api-slug: sound-cloud
  description: Returns a collection of tracks uploaded by user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/tracks.json
  tags: Users,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/usersuser-idtracks-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/usersuser-idtracks-json-get-openapi.md
- name: Sound Cloud Get Me Tracks
  x-api-slug: sound-cloud
  description: Returns a collection of tracks uploaded by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/tracks.json
  tags: Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/metracks-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/metracks-json-get-openapi.md
- name: Sound Cloud Get Groups Tracks
  x-api-slug: sound-cloud
  description: Returns a collection of tracks contributed to the group with group
    id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/tracks.json
  tags: Groups,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/groupsgroup-idtracks-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/groupsgroup-idtracks-json-get-openapi.md
- name: Sound Cloud Get Tracks. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks.{format}
  tags: Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/tracks-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/tracks-format-get-openapi.md
- name: Sound Cloud Post Tracks. Format
  x-api-slug: sound-cloud
  description: Post tracks. format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks.{format}
  tags: Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/tracks-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/tracks-format-post-openapi.md
- name: Sound Cloud Get Tracks Track . Format
  x-api-slug: sound-cloud
  description: Returns a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.{format}
  tags: Tracks,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-format-get-openapi.md
- name: Sound Cloud Put Tracks Track . Format
  x-api-slug: sound-cloud
  description: Put tracks track . format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.{format}
  tags: Tracks,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-format-put-openapi.md
- name: Sound Cloud Delete Tracks Track . Format
  x-api-slug: sound-cloud
  description: Delete tracks track . format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.{format}
  tags: Tracks,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-id-format-delete-openapi.md
- name: Sound Cloud Get Tracks Track Comments. Format
  x-api-slug: sound-cloud
  description: Returns comments of a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.{format}
  tags: Tracks,Track,Comments,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idcomments-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idcomments-format-get-openapi.md
- name: Sound Cloud Post Tracks Track Comments. Format
  x-api-slug: sound-cloud
  description: Posts a comments to a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.{format}
  tags: Tracks,Track,Comments,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idcomments-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idcomments-format-post-openapi.md
- name: Sound Cloud Get Tracks Track Permissions. Format
  x-api-slug: sound-cloud
  description: Returns all users with permission for a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/permissions.{format}
  tags: Tracks,Track,Permissions,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idpermissions-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idpermissions-format-get-openapi.md
- name: Sound Cloud Put Tracks Track Permissions. Format
  x-api-slug: sound-cloud
  description: Updates the list of permitted users for a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/permissions.{format}
  tags: Tracks,Track,Permissions,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idpermissions-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idpermissions-format-put-openapi.md
- name: Sound Cloud Get Tracks Track Secret Token. Format
  x-api-slug: sound-cloud
  description: Returns the secret token for a track by track id. This resource can
    only be used by the track owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/secret-token.{format}
  tags: Tracks,Track,Secret,Token,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idsecrettoken-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idsecrettoken-format-get-openapi.md
- name: Sound Cloud Put Tracks Track Secret Token. Format
  x-api-slug: sound-cloud
  description: |-
    Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on
                        the server and returned. This resource can only be used by the track owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/secret-token.{format}
  tags: Tracks,Track,Secret,Token,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idsecrettoken-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/trackstrack-idsecrettoken-format-put-openapi.md
- name: Sound Cloud Get Users Tracks. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks uploaded by user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/tracks.{format}
  tags: Users,Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/usersuser-idtracks-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/usersuser-idtracks-format-get-openapi.md
- name: Sound Cloud Get Me Tracks. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks uploaded by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/tracks.{format}
  tags: Me,Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/metracks-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/metracks-format-get-openapi.md
- name: Sound Cloud Get Groups Tracks. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks contributed to the group with group
    id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/tracks.{format}
  tags: Groups,Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/groupsgroup-idtracks-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/groupsgroup-idtracks-format-get-openapi.md
- name: Sound Cloud
  x-api-slug: sound-cloud
  description: SoundCloud is a music and podcast streaming platform that lets you
    listen to millions of songs from around the world, or upload your own. Start listening
    now!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com//
  tags: Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/soundcloud/openapi.md
x-common:
- type: x-base
  url: https://api.soundcloud.com
- type: x-blog
  url: http://blog.soundcloud.com
- type: x-blog-rss
  url: http://blog.soundcloud.com/feed/
- type: x-console
  url: https://developers.soundcloud.com/console
- type: x-crunchbase
  url: https://crunchbase.com/organization/soundcloud
- type: x-crunchbase
  url: http://www.crunchbase.com/company/soundcloud
- type: x-developer
  url: http://developers.soundcloud.com
- type: x-github
  url: https://github.com/soundcloud
- type: x-pricing
  url: https://on.soundcloud.com/
- type: x-privacy
  url: https://soundcloud.com/pages/privacy
- type: x-support
  url: https://soundcloud.com/imprint
- type: x-terms-of-service
  url: https://soundcloud.com/terms-of-use
- type: x-twitter
  url: https://twitter.com/soundcloudapi
- type: x-twitter
  url: https://twitter.com/SoundCloud
- type: x-website
  url: http://soundcloud.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
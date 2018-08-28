---
name: 7digital
x-slug: 7digital
description: Welcome to 7digital!    Choose from over 30 million high quality tracks
  in our store; download, sync and play your music on the go.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
x-kinRank: "7"
x-alexaRank: "55455"
tags: Tracks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/7digital/apis.md
specificationVersion: "0.14"
apis:
- name: 7digital Playlist API - playlists/{playlistId}/tracks/{playlisttrackid}
  x-api-slug: playlistsplaylistidtracksplaylisttrackid-delete
  description: Removes the specified track {playlisttrackid} from the specified playlist
    at {playlistId}.  Tracks can only be removed by the playlist owner, i.e. oauth_token
    representing the user has to be provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2/
  tags: Downloads, MP3, Streaming, Mobile, SaaS, Music, API Provider, Stores, Profiles,
    Publish, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/7digital/playlistsplaylistidtracksplaylisttrackid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/7digital/playlistsplaylistidtracksplaylisttrackid-delete-openapi.md
- name: 7digital Purchasing API - playlists/{playlistId}/tracks/{playlisttrackid}
  x-api-slug: playlistsplaylistidtracksplaylisttrackid-delete
  description: Removes the specified track {playlisttrackid} from the specified playlist
    at {playlistId}.  Tracks can only be removed by the playlist owner, i.e. oauth_token
    representing the user has to be provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/294-7digital.jpg
  humanURL: http://7digital.com
  baseURL: https://api.7digital.com/1.2/
  tags: Downloads, MP3, Streaming, Mobile, SaaS, Music, API Provider, Stores, Profiles,
    Publish, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/7digital/playlistsplaylistidtracksplaylisttrackid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/7digital/playlistsplaylistidtracksplaylisttrackid-delete-openapi.md
x-common:
- type: x--net-sdk
  url: https://github.com/7digital/SevenDigital.Api.Wrapper
- type: x-android-sdk
  url: http://developer.7digital.com/7digital-android-sdk
- type: x-api-gallery
  url: http://7digital.api.gallery.streamdata.io
- type: x-api-stack
  url: http://7digital.stack.network
- type: x-application-gallery
  url: http://developer.7digital.com/CaseStudies
- type: x-base
  url: http://api.7digital.com/
- type: x-blog
  url: http://developer.7digital.com/blog
- type: x-blog-rss
  url: http://blogs.7digital.com/dev/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/7digital
- type: x-crunchbase
  url: https://crunchbase.com/organization/7digital
- type: x-developer
  url: http://developer.7digital.net/
- type: x-email
  url: api@7digital.com
- type: x-email
  url: help@7digital.com
- type: x-email
  url: sales@7digital.com
- type: x-email
  url: legal@7digital.com
- type: x-email
  url: contention-queries@7digital.com
- type: x-github
  url: https://github.com/7digital
- type: x-ios-sdk
  url: https://github.com/7digital/7digital-iOS-SDK
- type: x-node-js-sdk
  url: https://github.com/raoulmillais/node-7digital-api
- type: x-php-sdk
  url: https://github.com/gquemener/7digital-client
- type: x-python-sdk
  url: https://github.com/jasonrubenstein/python-7Digital
- type: x-ruby-sdk
  url: http://github.com/filip7d/7digital
- type: x-selfservice-registration
  url: https://api-signup.7digital.com/
- type: x-twitter
  url: https://twitter.com/7digital
- type: x-website
  url: http://7digital.com
- type: x-website
  url: http://7digital.net/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
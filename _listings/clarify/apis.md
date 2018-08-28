---
name: Clarify
x-slug: clarify
description: The API to search, re-imagined for a world that???s moved beyond text.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
x-kinRank: "9"
x-alexaRank: "2476786"
tags: Tracks
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/clarify/apis.md
specificationVersion: "0.14"
apis:
- name: Clarify Delete bundle tracks
  x-api-slug: clarify
  description: Delete tracks of a bundle. This will only delete media stored on Clarify
    systems and not delete the source media on remote systems.Successful response
    will be a HTTP code 204 with an empty body.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
  humanURL: http://clarify.io/
  baseURL: https://api.clarify.io////v1/bundles/{bundle_id}/tracks
  tags: Bundle,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/clarify/v1bundlesbundle-idtracks-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/clarify/v1bundlesbundle-idtracks-delete-openapi.md
- name: Clarify Get bundle tracks
  x-api-slug: clarify
  description: Gets the array of tracks for a bundle. This includes the specification
    of the media and the status of fetching and processing it.Media for tracks is
    fetched asynchronously. Until media has been retrieved, a track&apos;s duration
    and size will both be set to -1.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
  humanURL: http://clarify.io/
  baseURL: https://api.clarify.io////v1/bundles/{bundle_id}/tracks
  tags: Bundle,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/clarify/v1bundlesbundle-idtracks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/clarify/v1bundlesbundle-idtracks-get-openapi.md
- name: Clarify Update a tracks for a bundle
  x-api-slug: clarify
  description: Update tracks for a bundle.parts_complete a boolean true or false.
    If true, any tracks in the PENDING state will be queued for processing and no
    more media parts may be added to the tracks. Default is false.If version specified,
    the track will only be updated if the current version matches this parameter value.
    If the version doesn't match, a 409 Conflict error will be returned. If version
    not specified, the track will always be updated.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
  humanURL: http://clarify.io/
  baseURL: https://api.clarify.io////v1/bundles/{bundle_id}/tracks
  tags: Tracksa,Bundle
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/clarify/v1bundlesbundle-idtracks-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/clarify/v1bundlesbundle-idtracks-put-openapi.md
- name: Clarify
  x-api-slug: clarify
  description: The API to search, re-imagined for a world that???s moved beyond text.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
  humanURL: http://clarify.io/
  baseURL: https://api.clarify.io//
  tags: Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/clarify/openapi.md
x-common:
- type: x-base
  url: https://api.clarify.io
- type: x-blog
  url: http://clarify.io/blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/clarify-inc
- type: x-developer
  url: http://developer.clarify.io/
- type: x-documentation
  url: http://clarify.io/docs/api/
- type: x-email
  url: contact@clarify.io
- type: x-email
  url: cfy.dmca@clarify.io
- type: x-github
  url: https://github.com/OP3Nvoice
- type: x-pricing
  url: http://clarify.io/pricing/
- type: x-twitter
  url: https://twitter.com/ClarifyAPI
- type: x-twitter
  url: https://twitter.com/clarifyio
- type: x-website
  url: http://clarify.io/
- type: x-website
  url: http://clarify.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
---
name: Washington Metropolitan Area Transit Authority
x-slug: washington-metropolitan-area-transit-authority
description: Official feed of Metro/WMATA, not monitored 24/7. Report emergencies
  to Transit Police at (202) 962-2121. Service updates @metrorailinfo & @metrobusinfo.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1214-washington-metropolitan-area-transit-authority.jpg
x-kinRank: "8"
x-alexaRank: "24927"
tags: Tracks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/washington-metropolitan-area-transit-authority/apis.md
specificationVersion: "0.14"
apis:
- name: Train Positions - Track Circuits
  x-api-slug: trackcircuits-get
  description: "Description\r\n\r\nReturns a list of all track circuits including
    those on pocket tracks and crossovers.  Each track circuit may include references
    to its right and left neighbors.\r\nPlease refer to this page for additional details.\r\n\r\nResponse
    Elements\r\n\r\n\r\n\r\n\r\nElement\r\n\r\nDescription\r\n\r\n\r\n\r\n\r\n\r\nTrackCircuits\r\n\r\n\r\nArray
    containing track circuit information (TrackCircuit).\r\n\r\n\r\n\r\n\r\n\r\n\r\nTrackCircuit
    Elements\r\n\r\n\r\n\r\n\r\n\r\nCircuitId\r\n\r\nAn internal system-wide uniquely
    identifiable circuit number.\r\n\r\n\r\n\r\nNeighbors\r\n\r\n\r\nArray containing
    track circuit neighbor information (TrackCircuitNeighbor).  Note that some track
    circuits have no neighbors in one direction.  All track circuits have at least
    one neighbor.\r\n\r\n\r\n\r\n\r\nTrack\r\n\r\nTrack number.  1 and 2 denote \"main\"
    lines, while 0 and 3 are connectors (between different types of tracks) and pocket
    tracks, respectively.\r\n\r\n\r\n\r\n\r\n\r\nTrackCircuitNeighbor Elements\r\n\r\n\r\n\r\n\r\n\r\nCircuitIds\r\n\r\n\r\nArray
    containing neighboring circuit ids.\r\n\r\n\r\n\r\n\r\nNeighborType\r\n\r\nLeft
    or Right neighbor group.  Generally speaking, left neighbors are to the west and
    south, while right neighbors are to the east/north.\r\n\r\n\r\n\r\n\r\nNeighbor
    Notes\r\n\r\nGiven the hypothetical example below, note that CircuitId 8 has two
    right neighbors - 4 and 3.  Similarly, CircuitId 6 has two left neighbors - 5
    and 7.\r\n\r\n\r\n\r\n\r\n\r\nbackground\r\n\r\n\r\n\r\nLayer 1\r\nTrack 2\r\n\r\n8\r\n\r\n4\r\nTrack
    1\r\n\r\nCircuitId 1\r\n\r\n2\r\n\r\nCircuitId 4\r\n\r\n9\r\n\r\n\r\n100\r\n\r\n3\r\n\r\nTrack
    0\r\nTrack 0\r\nTrack 3\r\n7\r\n5\r\n\r\n6\r\n\r\n\r\n\r\nThe JSON representation
    of the image above would be as follows:\r\n\r\n\r\n{\r\n\"TrackCircuits\": [{\r\n\"Track\":
    2,\r\n\"CircuitId\": 8,\r\n\"Neighbors\": [{\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\":
    [4, 3]\r\n}]\r\n}, {\r\n\"Track\": 2,\r\n\"CircuitId\": 4,\r\n\"Neighbors\": [{\r\n\"NeighborType\":
    \"Left\",\r\n\"CircuitIds\": [8]\r\n}, {\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\":
    [9]\r\n}]\r\n}, {\r\n\"Track\": 2,\r\n\"CircuitId\": 9,\r\n\"Neighbors\": [{\r\n\"NeighborType\":
    \"Left\",\r\n\"CircuitIds\": [4]\r\n}]\r\n}, {\r\n\"Track\": 0,\r\n\"CircuitId\":
    3,\r\n\"Neighbors\": [{\r\n\"NeighborType\": \"Left\",\r\n\"CircuitIds\": [8]\r\n},
    {\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\": [100]\r\n}]\r\n}, {\r\n\"Track\":
    3,\r\n\"CircuitId\": 100,\r\n\"Neighbors\": [{\r\n\"NeighborType\": \"Left\",\r\n\"CircuitIds\":
    [3]\r\n}, {\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\": [7]\r\n}]\r\n},
    {\r\n\"Track\": 0,\r\n\"CircuitId\": 7,\r\n\"Neighbors\": [{\r\n\"NeighborType\":
    \"Left\",\r\n\"CircuitIds\": [100]\r\n}, {\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\":
    [6]\r\n}]\r\n}, {\r\n\"Track\": 1,\r\n\"CircuitId\": 1,\r\n\"Neighbors\": [{\r\n\"NeighborType\":
    \"Right\",\r\n\"CircuitIds\": [2]\r\n}]\r\n}, {\r\n\"Track\": 1,\r\n\"CircuitId\":
    2,\r\n\"Neighbors\": [{\r\n\"NeighborType\": \"Left\",\r\n\"CircuitIds\": [1]\r\n},
    {\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\": [5]\r\n}]\r\n}, {\r\n\"Track\":
    1,\r\n\"CircuitId\": 5,\r\n\"Neighbors\": [{\r\n\"NeighborType\": \"Left\",\r\n\"CircuitIds\":
    [2]\r\n}, {\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\": [6]\r\n}]\r\n},
    {\r\n\"Track\": 1,\r\n\"CircuitId\": 6,\r\n\"Neighbors\": [{\r\n\"NeighborType\":
    \"Left\",\r\n\"CircuitIds\": [5, 7]\r\n}]\r\n}]\r\n}"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1214-washington-metropolitan-area-transit-authority.jpg
  humanURL: http://wmata.com/
  baseURL: https://api.wmata.com//TrainPositions
  tags: Transit, Transit, Transportation, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/washington-metropolitan-area-transit-authority/trackcircuits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracks/master/_listings/washington-metropolitan-area-transit-authority/trackcircuits-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://vzaar.api.gallery.streamdata.io
- type: x-api-stack
  url: http://washington.metropolitan.area.transit.authority.stack.network
- type: x-base
  url: http://api.wmata.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/wmata
- type: x-developer
  url: http://developer.wmata.com/
- type: x-email
  url: boardofdirectors@wmata.com
- type: x-email
  url: metrotransit@wmata.com
- type: x-email
  url: adaassist@wmata.com
- type: x-email
  url: access@wmata.com
- type: x-email
  url: cjachles@wmata.com
- type: x-email
  url: writtentestimony@wmata.com
- type: x-email
  url: speak@wmata.com
- type: x-email
  url: SEBusMove@wmata.com
- type: x-email
  url: PARP@wmata.com
- type: x-email
  url: raccomments@wmata.com
- type: x-signup
  url: https://developer.wmata.com/signup/
- type: x-twitter
  url: https://twitter.com/wmata
- type: x-website
  url: http://wmata.com/
- type: x-website
  url: http://wmata.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
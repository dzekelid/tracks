---
swagger: "2.0"
x-collection-name: Washington Metropolitan Area Transit Authority
x-complete: 1
info:
  title: Train Positions
  description: realtime-train-positions-and-support-methods-
  version: 1.0.0
host: api.wmata.com
basePath: /TrainPositions
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /TrackCircuits:
    get:
      summary: Track Circuits
      description: "Description\r\n\r\nReturns a list of all track circuits including
        those on pocket tracks and crossovers.  Each track circuit may include references
        to its right and left neighbors.\r\nPlease refer to this page for additional
        details.\r\n\r\nResponse Elements\r\n\r\n\r\n\r\n\r\nElement\r\n\r\nDescription\r\n\r\n\r\n\r\n\r\n\r\nTrackCircuits\r\n\r\n\r\nArray
        containing track circuit information (TrackCircuit).\r\n\r\n\r\n\r\n\r\n\r\n\r\nTrackCircuit
        Elements\r\n\r\n\r\n\r\n\r\n\r\nCircuitId\r\n\r\nAn internal system-wide uniquely
        identifiable circuit number.\r\n\r\n\r\n\r\nNeighbors\r\n\r\n\r\nArray containing
        track circuit neighbor information (TrackCircuitNeighbor).  Note that some
        track circuits have no neighbors in one direction.  All track circuits have
        at least one neighbor.\r\n\r\n\r\n\r\n\r\nTrack\r\n\r\nTrack number.  1 and
        2 denote \"main\" lines, while 0 and 3 are connectors (between different types
        of tracks) and pocket tracks, respectively.\r\n\r\n\r\n\r\n\r\n\r\nTrackCircuitNeighbor
        Elements\r\n\r\n\r\n\r\n\r\n\r\nCircuitIds\r\n\r\n\r\nArray containing neighboring
        circuit ids.\r\n\r\n\r\n\r\n\r\nNeighborType\r\n\r\nLeft or Right neighbor
        group.  Generally speaking, left neighbors are to the west and south, while
        right neighbors are to the east/north.\r\n\r\n\r\n\r\n\r\nNeighbor Notes\r\n\r\nGiven
        the hypothetical example below, note that CircuitId 8 has two right neighbors
        - 4 and 3.  Similarly, CircuitId 6 has two left neighbors - 5 and 7.\r\n\r\n\r\n\r\n\r\n\r\nbackground\r\n\r\n\r\n\r\nLayer
        1\r\nTrack 2\r\n\r\n8\r\n\r\n4\r\nTrack 1\r\n\r\nCircuitId 1\r\n\r\n2\r\n\r\nCircuitId
        4\r\n\r\n9\r\n\r\n\r\n100\r\n\r\n3\r\n\r\nTrack 0\r\nTrack 0\r\nTrack 3\r\n7\r\n5\r\n\r\n6\r\n\r\n\r\n\r\nThe
        JSON representation of the image above would be as follows:\r\n\r\n\r\n{\r\n\"TrackCircuits\":
        [{\r\n\"Track\": 2,\r\n\"CircuitId\": 8,\r\n\"Neighbors\": [{\r\n\"NeighborType\":
        \"Right\",\r\n\"CircuitIds\": [4, 3]\r\n}]\r\n}, {\r\n\"Track\": 2,\r\n\"CircuitId\":
        4,\r\n\"Neighbors\": [{\r\n\"NeighborType\": \"Left\",\r\n\"CircuitIds\":
        [8]\r\n}, {\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\": [9]\r\n}]\r\n},
        {\r\n\"Track\": 2,\r\n\"CircuitId\": 9,\r\n\"Neighbors\": [{\r\n\"NeighborType\":
        \"Left\",\r\n\"CircuitIds\": [4]\r\n}]\r\n}, {\r\n\"Track\": 0,\r\n\"CircuitId\":
        3,\r\n\"Neighbors\": [{\r\n\"NeighborType\": \"Left\",\r\n\"CircuitIds\":
        [8]\r\n}, {\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\": [100]\r\n}]\r\n},
        {\r\n\"Track\": 3,\r\n\"CircuitId\": 100,\r\n\"Neighbors\": [{\r\n\"NeighborType\":
        \"Left\",\r\n\"CircuitIds\": [3]\r\n}, {\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\":
        [7]\r\n}]\r\n}, {\r\n\"Track\": 0,\r\n\"CircuitId\": 7,\r\n\"Neighbors\":
        [{\r\n\"NeighborType\": \"Left\",\r\n\"CircuitIds\": [100]\r\n}, {\r\n\"NeighborType\":
        \"Right\",\r\n\"CircuitIds\": [6]\r\n}]\r\n}, {\r\n\"Track\": 1,\r\n\"CircuitId\":
        1,\r\n\"Neighbors\": [{\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\":
        [2]\r\n}]\r\n}, {\r\n\"Track\": 1,\r\n\"CircuitId\": 2,\r\n\"Neighbors\":
        [{\r\n\"NeighborType\": \"Left\",\r\n\"CircuitIds\": [1]\r\n}, {\r\n\"NeighborType\":
        \"Right\",\r\n\"CircuitIds\": [5]\r\n}]\r\n}, {\r\n\"Track\": 1,\r\n\"CircuitId\":
        5,\r\n\"Neighbors\": [{\r\n\"NeighborType\": \"Left\",\r\n\"CircuitIds\":
        [2]\r\n}, {\r\n\"NeighborType\": \"Right\",\r\n\"CircuitIds\": [6]\r\n}]\r\n},
        {\r\n\"Track\": 1,\r\n\"CircuitId\": 6,\r\n\"Neighbors\": [{\r\n\"NeighborType\":
        \"Left\",\r\n\"CircuitIds\": [5, 7]\r\n}]\r\n}]\r\n}"
      operationId: getTrackcircuits
      x-api-path-slug: trackcircuits-get
      parameters:
      - in: query
        name: contentType
        description: Returns response in the specified format
      responses:
        200:
          description: OK
      tags:
      - Transit
      - Subway
      - Tracks
      - Circuits
---
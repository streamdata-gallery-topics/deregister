swagger: "2.0"
x-collection-name: Vinli
x-complete: 1
info:
  title: Vinli
  description: todo-add-description
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /devices/821374c0-d6d8-11e3-9c1a-0800200c9a66:
    delete:
      summary: Deregister a Device
      description: Deregister a device.
      operationId: Devices821374c0D6d811e39c1a0800200c9a66Delete
      x-api-path-slug: devices821374c0d6d811e39c1a0800200c9a66-delete
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Device
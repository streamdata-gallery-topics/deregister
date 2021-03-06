---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 0
info:
  title: AWS OpsWorks API Deregister Instance
  version: 1.0.0
  description: Deregister a registered Amazon EC2 or on-premises instance.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeregisterEcsCluster:
    get:
      summary: Deregister Ecs Cluster
      description: Deregisters a specified Amazon ECS cluster from a stack.
      operationId: deregisterEcsCluster
      x-api-path-slug: actionderegisterecscluster-get
      parameters:
      - in: query
        name: EcsClusterArn
        description: The clusters ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Ecs
      - Cluster
  /?Action=DeregisterElasticIp:
    get:
      summary: Deregister Elastic IP
      description: Deregisters a specified Elastic IP address.
      operationId: deregisterElasticIp
      x-api-path-slug: actionderegisterelasticip-get
      parameters:
      - in: query
        name: ElasticIp
        description: The Elastic IP address
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Elastic
      - IP Addresses
  /?Action=DeregisterInstance:
    get:
      summary: Deregister Instance
      description: Deregister a registered Amazon EC2 or on-premises instance.
      operationId: deregisterInstance
      x-api-path-slug: actionderegisterinstance-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Instance
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
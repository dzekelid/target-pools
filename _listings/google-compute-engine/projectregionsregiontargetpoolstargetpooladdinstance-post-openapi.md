---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Add Instance to Target pool
  description: Adds an instance to a target pool.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /compute/v1/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/aggregated/targetPools:
    get:
      summary: Get Target Pools
      description: Retrieves an aggregated list of target pools.
      operationId: compute.targetPools.aggregatedList
      x-api-path-slug: projectaggregatedtargetpools-get
      parameters:
      - in: query
        name: filter
        description: Sets a filter expression for filtering listed resources, in the
          form filter={expression}
      - in: query
        name: maxResults
        description: The maximum number of results per page that should be returned
      - in: query
        name: orderBy
        description: Sorts list results by a certain order
      - in: query
        name: pageToken
        description: Specifies a page token to use
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Target Pools
      - Aggregation
  /{project}/regions/{region}/targetPools:
    get:
      summary: Get Target Pools
      description: Retrieves a list of target pools available to the specified project
        and region.
      operationId: compute.targetPools.list
      x-api-path-slug: projectregionsregiontargetpools-get
      parameters:
      - in: query
        name: filter
        description: Sets a filter expression for filtering listed resources, in the
          form filter={expression}
      - in: query
        name: maxResults
        description: The maximum number of results per page that should be returned
      - in: query
        name: orderBy
        description: Sorts list results by a certain order
      - in: query
        name: pageToken
        description: Specifies a page token to use
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region scoping this request
      responses:
        200:
          description: OK
      tags:
      - Target Pool
    post:
      summary: Create Target Pool
      description: Creates a target pool in the specified project and region using
        the data included in the request.
      operationId: compute.targetPools.insert
      x-api-path-slug: projectregionsregiontargetpools-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region scoping this request
      responses:
        200:
          description: OK
      tags:
      - Target Pool
  /{project}/regions/{region}/targetPools/{targetPool}:
    delete:
      summary: Delete Target Pool
      description: Deletes the specified target pool.
      operationId: compute.targetPools.delete
      x-api-path-slug: projectregionsregiontargetpoolstargetpool-delete
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region scoping this request
      - in: path
        name: targetPool
        description: Name of the TargetPool resource to delete
      responses:
        200:
          description: OK
      tags:
      - Target Pool
    get:
      summary: Get Target Pool
      description: Returns the specified target pool. Get a list of available target
        pools by making a list() request.
      operationId: compute.targetPools.get
      x-api-path-slug: projectregionsregiontargetpoolstargetpool-get
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region scoping this request
      - in: path
        name: targetPool
        description: Name of the TargetPool resource to return
      responses:
        200:
          description: OK
      tags:
      - Target Pool
  /{project}/regions/{region}/targetPools/{targetPool}/addHealthCheck:
    post:
      summary: Add Target Pool Health Check
      description: Adds health check URLs to a target pool.
      operationId: compute.targetPools.addHealthCheck
      x-api-path-slug: projectregionsregiontargetpoolstargetpooladdhealthcheck-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region scoping this request
      - in: path
        name: targetPool
        description: Name of the target pool to add a health check to
      responses:
        200:
          description: OK
      tags:
      - Target Pool
  /{project}/regions/{region}/targetPools/{targetPool}/addInstance:
    post:
      summary: Add Instance to Target pool
      description: Adds an instance to a target pool.
      operationId: compute.targetPools.addInstance
      x-api-path-slug: projectregionsregiontargetpoolstargetpooladdinstance-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region scoping this request
      - in: path
        name: targetPool
        description: Name of the TargetPool resource to add instances to
      responses:
        200:
          description: OK
      tags:
      - Target Pool
  /{project}/regions/{region}/targetPools/{targetPool}/getHealth:
    post:
      summary: Get Target Pool Health Check
      description: Gets the most recent health check results for each IP for the instance
        that is referenced by the given target pool.
      operationId: compute.targetPools.getHealth
      x-api-path-slug: projectregionsregiontargetpoolstargetpoolgethealth-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region scoping this request
      - in: path
        name: targetPool
        description: Name of the TargetPool resource to which the queried instance
          belongs
      responses:
        200:
          description: OK
      tags:
      - Target Pool
  /{project}/regions/{region}/targetPools/{targetPool}/removeHealthCheck:
    post:
      summary: Remove Target Pool  Health Check
      description: Removes health check URL from a target pool.
      operationId: compute.targetPools.removeHealthCheck
      x-api-path-slug: projectregionsregiontargetpoolstargetpoolremovehealthcheck-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region for this request
      - in: path
        name: targetPool
        description: Name of the target pool to remove health checks from
      responses:
        200:
          description: OK
      tags:
      - Target Pool
  /{project}/regions/{region}/targetPools/{targetPool}/removeInstance:
    post:
      summary: Remove Instance From Target Pool
      description: Removes instance URL from a target pool.
      operationId: compute.targetPools.removeInstance
      x-api-path-slug: projectregionsregiontargetpoolstargetpoolremoveinstance-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region scoping this request
      - in: path
        name: targetPool
        description: Name of the TargetPool resource to remove instances from
      responses:
        200:
          description: OK
      tags:
      - Target Pool
  /{project}/regions/{region}/targetPools/{targetPool}/setBackup:
    post:
      summary: Change Target Pool Backup
      description: Changes a backup target pool's configurations.
      operationId: compute.targetPools.setBackup
      x-api-path-slug: projectregionsregiontargetpoolstargetpoolsetbackup-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: failoverRatio
        description: New failoverRatio value for the target pool
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region scoping this request
      - in: path
        name: targetPool
        description: Name of the TargetPool resource to set a backup pool for
      responses:
        200:
          description: OK
      tags:
      - Target Pool
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
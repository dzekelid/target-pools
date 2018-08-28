---
name: Google Compute Engine
x-slug: google-compute-engine
description: Google Compute Engine delivers virtual machines running in Googles innovative
  data centers and worldwide fiber network. Compute Engines tooling and workflow support
  enable scaling from single instances to global, load-balanced cloud computing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Target Pools
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Compute Engine - Get Target Pools
  x-api-slug: projectaggregatedtargetpools-get
  description: Retrieves an aggregated list of target pools.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectaggregatedtargetpools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectaggregatedtargetpools-get-openapi.md
- name: Compute Engine - Get Target Pools
  x-api-slug: projectregionsregiontargetpools-get
  description: Retrieves a list of target pools available to the specified project
    and region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpools-get-openapi.md
- name: Compute Engine - Create Target Pool
  x-api-slug: projectregionsregiontargetpools-post
  description: Creates a target pool in the specified project and region using the
    data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpools-post-openapi.md
- name: Compute Engine - Delete Target Pool
  x-api-slug: projectregionsregiontargetpoolstargetpool-delete
  description: Deletes the specified target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpool-delete-openapi.md
- name: Compute Engine - Get Target Pool
  x-api-slug: projectregionsregiontargetpoolstargetpool-get
  description: Returns the specified target pool. Get a list of available target pools
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpool-get-openapi.md
- name: Compute Engine - Add Target Pool Health Check
  x-api-slug: projectregionsregiontargetpoolstargetpooladdhealthcheck-post
  description: Adds health check URLs to a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpooladdhealthcheck-post-openapi.md
- name: Compute Engine - Add Instance to Target pool
  x-api-slug: projectregionsregiontargetpoolstargetpooladdinstance-post
  description: Adds an instance to a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpooladdinstance-post-openapi.md
- name: Compute Engine - Get Target Pool Health Check
  x-api-slug: projectregionsregiontargetpoolstargetpoolgethealth-post
  description: Gets the most recent health check results for each IP for the instance
    that is referenced by the given target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolgethealth-post-openapi.md
- name: Compute Engine - Remove Target Pool  Health Check
  x-api-slug: projectregionsregiontargetpoolstargetpoolremovehealthcheck-post
  description: Removes health check URL from a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolremovehealthcheck-post-openapi.md
- name: Compute Engine - Remove Instance From Target Pool
  x-api-slug: projectregionsregiontargetpoolstargetpoolremoveinstance-post
  description: Removes instance URL from a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolremoveinstance-post-openapi.md
- name: Compute Engine - Change Target Pool Backup
  x-api-slug: projectregionsregiontargetpoolstargetpoolsetbackup-post
  description: Changes a backup target pool's configurations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolsetbackup-post-openapi.md
- name: Compute Engine - Get Target Pools
  x-api-slug: projectregionsregiontargetpools-get
  description: Retrieves a list of target pools available to the specified project
    and region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpools-get-openapi.md
- name: Compute Engine - Create Target Pool
  x-api-slug: projectregionsregiontargetpools-post
  description: Creates a target pool in the specified project and region using the
    data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpools-post-openapi.md
- name: Compute Engine - Delete Target Pool
  x-api-slug: projectregionsregiontargetpoolstargetpool-delete
  description: Deletes the specified target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpool-delete-openapi.md
- name: Compute Engine - Get Target Pool
  x-api-slug: projectregionsregiontargetpoolstargetpool-get
  description: Returns the specified target pool. Get a list of available target pools
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpool-get-openapi.md
- name: Compute Engine - Add Target Pool Health Check
  x-api-slug: projectregionsregiontargetpoolstargetpooladdhealthcheck-post
  description: Adds health check URLs to a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpooladdhealthcheck-post-openapi.md
- name: Compute Engine - Add Instance to Target pool
  x-api-slug: projectregionsregiontargetpoolstargetpooladdinstance-post
  description: Adds an instance to a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpooladdinstance-post-openapi.md
- name: Compute Engine - Get Target Pool Health Check
  x-api-slug: projectregionsregiontargetpoolstargetpoolgethealth-post
  description: Gets the most recent health check results for each IP for the instance
    that is referenced by the given target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolgethealth-post-openapi.md
- name: Compute Engine - Remove Target Pool  Health Check
  x-api-slug: projectregionsregiontargetpoolstargetpoolremovehealthcheck-post
  description: Removes health check URL from a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolremovehealthcheck-post-openapi.md
- name: Compute Engine - Remove Instance From Target Pool
  x-api-slug: projectregionsregiontargetpoolstargetpoolremoveinstance-post
  description: Removes instance URL from a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolremoveinstance-post-openapi.md
- name: Compute Engine - Change Target Pool Backup
  x-api-slug: projectregionsregiontargetpoolstargetpoolsetbackup-post
  description: Changes a backup target pool's configurations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolsetbackup-post-openapi.md
- name: Compute Engine - Get Target Pools
  x-api-slug: projectregionsregiontargetpools-get
  description: Retrieves a list of target pools available to the specified project
    and region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpools-get-openapi.md
- name: Compute Engine - Create Target Pool
  x-api-slug: projectregionsregiontargetpools-post
  description: Creates a target pool in the specified project and region using the
    data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpools-post-openapi.md
- name: Compute Engine - Delete Target Pool
  x-api-slug: projectregionsregiontargetpoolstargetpool-delete
  description: Deletes the specified target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpool-delete-openapi.md
- name: Compute Engine - Get Target Pool
  x-api-slug: projectregionsregiontargetpoolstargetpool-get
  description: Returns the specified target pool. Get a list of available target pools
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpool-get-openapi.md
- name: Compute Engine - Add Target Pool Health Check
  x-api-slug: projectregionsregiontargetpoolstargetpooladdhealthcheck-post
  description: Adds health check URLs to a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpooladdhealthcheck-post-openapi.md
- name: Compute Engine - Add Instance to Target pool
  x-api-slug: projectregionsregiontargetpoolstargetpooladdinstance-post
  description: Adds an instance to a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpooladdinstance-post-openapi.md
- name: Compute Engine - Get Target Pool Health Check
  x-api-slug: projectregionsregiontargetpoolstargetpoolgethealth-post
  description: Gets the most recent health check results for each IP for the instance
    that is referenced by the given target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolgethealth-post-openapi.md
- name: Compute Engine - Remove Target Pool  Health Check
  x-api-slug: projectregionsregiontargetpoolstargetpoolremovehealthcheck-post
  description: Removes health check URL from a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolremovehealthcheck-post-openapi.md
- name: Compute Engine - Remove Instance From Target Pool
  x-api-slug: projectregionsregiontargetpoolstargetpoolremoveinstance-post
  description: Removes instance URL from a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolremoveinstance-post-openapi.md
- name: Compute Engine - Change Target Pool Backup
  x-api-slug: projectregionsregiontargetpoolstargetpoolsetbackup-post
  description: Changes a backup target pool's configurations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target-pools/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolsetbackup-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.vision.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.compute.engine.stack.network
- type: x-code
  url: https://cloud.google.com/compute/docs/api/libraries
- type: x-documentation
  url: https://cloud.google.com/compute/docs/reference/latest/
- type: x-guides
  url: https://cloud.google.com/compute/docs/api/how-tos/how-tos
- type: x-rate-limits
  url: https://cloud.google.com/compute/docs/api-rate-limits
- type: x-sla
  url: https://cloud.google.com/compute/sla
- type: x-website
  url: https://cloud.google.com/compute/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
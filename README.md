# CubeFS (cubefs)

CubeFS is a CNCF graduated cloud-native distributed file system supporting POSIX, HDFS, and S3-compatible object storage protocols. It provides multi-tenancy, multi-AZ deployment, cross-region replication, and erasure coding for both hot and cold data tiers. CubeFS is widely used to back cloud-native AI training, big-data analytics, and container storage workloads.

**APIs.yml URL:** https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **x-type:** opensource
- **Governance:** CNCF Graduated

## Tags

Cloud Native, CNCF Graduated, Distributed File System, Kubernetes, Object Storage, POSIX, S3 Compatible, Storage

## APIs

### CubeFS S3-Compatible API

ObjectNode-fronted S3 API for buckets, objects, multipart uploads, and access control.

- Documentation: https://cubefs.io/docs/master/user-guide/objectnode.html
- OpenAPI: [openapi/cubefs-s3-api-openapi.yml](openapi/cubefs-s3-api-openapi.yml)

### CubeFS Master API

Cluster management API for volumes, partitions, data and meta nodes, users, and cluster status.

- Documentation: https://cubefs.io/docs/master/dev-guide/master-api.html
- OpenAPI: [openapi/cubefs-master-api-openapi.yml](openapi/cubefs-master-api-openapi.yml)

## Features

- Multi-protocol access (POSIX/FUSE, HDFS, S3)
- Multi-tenancy with user/access-key isolation
- Multi-AZ deployment with cross-zone partitions
- Erasure coding for cold-data tiers
- Kubernetes CSI driver for persistent volumes
- Master control plane HTTP API
- ObjectNode S3 gateway compatible with AWS SDKs
- CNCF graduated governance

## Use Cases

- AI/ML training dataset storage
- Big-data analytics via HDFS clients
- Cloud-native S3-compatible object storage
- Kubernetes RWX persistent volumes
- Multi-region storage and disaster recovery
- Hot/cold data tiering with replication and erasure coding

## Artifacts

- OpenAPI (Master): [openapi/cubefs-master-api-openapi.yml](openapi/cubefs-master-api-openapi.yml)
- OpenAPI (S3): [openapi/cubefs-s3-api-openapi.yml](openapi/cubefs-s3-api-openapi.yml)
- JSON Schema: [json-schema/cubefs-volume-schema.json](json-schema/cubefs-volume-schema.json)
- JSON-LD Context: [json-ld/cubefs-context.jsonld](json-ld/cubefs-context.jsonld)
- Vocabulary: [vocabulary/cubefs-vocabulary.yml](vocabulary/cubefs-vocabulary.yml)
- Spectral Rules: [rules/](rules/)
- Naftiko Capabilities: [capabilities/](capabilities/)

## Maintainers

- Kin Lane (kin@apievangelist.com)

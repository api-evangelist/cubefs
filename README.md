# CubeFS (cubefs)

CubeFS is a CNCF graduated cloud-native distributed file system supporting POSIX, HDFS, and S3-compatible object storage protocols. It provides multi-tenancy, multi-AZ deployment, cross-region replication, and erasure coding for both hot and cold data tiers, and is widely used to back cloud-native AI training, big-data analytics, and container storage workloads.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cloud Native
- CNCF Graduated
- Distributed File System
- Kubernetes
- Object Storage
- POSIX
- S3 Compatible
- Storage

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### CubeFS S3-Compatible API

CubeFS exposes an S3-compatible object storage interface through its ObjectNode component. AWS S3 SDKs work without modification for bucket management, object CRUD, multipart uploads, and access control.

- **Human URL:** [https://cubefs.io/docs/master/user-guide/objectnode.html](https://cubefs.io/docs/master/user-guide/objectnode.html)

#### Tags

- Compatible API
- Object Storage
- S3

#### Properties

- [Documentation](https://cubefs.io/docs/master/user-guide/objectnode.html)
- [GitHub Repository](https://github.com/cubefs/cubefs)
- [OpenAPI](openapi/cubefs-s3-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cubefs-s3-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cubefs-s3-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/cubefs-s3-rules.yml)

### CubeFS Master API

The CubeFS Master API provides HTTP endpoints for cluster management including volume creation/deletion, data and meta partition management, data and meta node management, user/policy management, and cluster status monitoring. It is the control plane interface for administering CubeFS clusters.

- **Human URL:** [https://cubefs.io/docs/master/dev-guide/master-api.html](https://cubefs.io/docs/master/dev-guide/master-api.html)

#### Tags

- Admin API
- Cluster Management
- Control Plane

#### Properties

- [Documentation](https://cubefs.io/docs/master/dev-guide/master-api.html)
- [GitHub Repository](https://github.com/cubefs/cubefs)
- [OpenAPI](openapi/cubefs-master-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cubefs-master-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cubefs-master-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cubefs-volume-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/cubefs-master-rules.yml)

## Common Properties

- [JSON-LD](json-ld/cubefs-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/cubefs-volume-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/cubefs-vocabulary.yml)
- [Spectral Rules](rules/cubefs-master-rules.yml)
- [Spectral Rules](rules/cubefs-s3-rules.yml)
- [Website](https://cubefs.io/)
- [Documentation](https://cubefs.io/docs/master/overview/introduction.html)
- [Getting Started](https://cubefs.io/docs/master/quickstart/single-deploy.html)
- [Changelog](https://github.com/cubefs/cubefs/blob/master/CHANGELOG.md)
- [GitHub Organization](https://github.com/cubefs)
- [GitHub Repository](https://github.com/cubefs/cubefs)
- [L L Ms Txt](https://cubefs.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

# Schema Evolution (schema-evolution)

Schema Evolution is the practice of managing changes to data schemas over time while preserving compatibility between producers and consumers. It covers backward compatibility, forward compatibility, full compatibility, breaking change detection, schema migration strategies, and versioning patterns for REST APIs, event streaming (Kafka/Avro), GraphQL, database schemas, and Protocol Buffers. Effective schema evolution is critical for maintaining API contracts and enabling independent deployment of distributed system components.

**APIs.json:** [https://github.com/api-evangelist/schema-evolution](https://github.com/api-evangelist/schema-evolution)

## Tags

- Schema Evolution
- Backward Compatibility
- Forward Compatibility
- API Versioning
- Breaking Changes
- Schema Registry
- Data Migration
- Kafka

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Confluent Schema Registry API

The Confluent Schema Registry provides a serving layer for your metadata. It provides a RESTful interface for storing and retrieving your Avro, JSON Schema, and Protobuf schemas. It stores a versioned history of all schemas based on a specified subject name strategy, provides multiple compatibility settings and allows evolution of schemas according to the configured compatibility setting. It is used by Kafka producers and consumers to enforce schema compatibility when reading and writing Kafka messages.

- **Human URL:** [https://docs.confluent.io/platform/current/schema-registry/develop/api.html](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)
- **Base URL:** `https://your-schema-registry-host/`

#### Tags

- Schema Registry
- Confluent
- Kafka
- Avro
- Compatibility

#### Properties

- [Documentation](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)
- [Reference](https://docs.confluent.io/platform/current/schema-registry/fundamentals/schema-evolution.html)
- [OpenAPI](openapi/schema-evolution-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/schema-evolution.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schema-evolution.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AWS Glue Schema Registry API

AWS Glue Schema Registry is a feature that enables you to centrally discover, control, and evolve data stream schemas. The AWS Glue Schema Registry API supports creating, deleting, listing, updating, and fetching schemas, and it supports compatibility checking for Avro and JSON Schema formats.

- **Human URL:** [https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html](https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html)
- **Base URL:** `https://glue.us-east-1.amazonaws.com`

#### Tags

- AWS
- Schema Registry
- Cloud
- Avro

#### Properties

- [Documentation](https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html)
- [Postman Collection](collections/schema-evolution.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schema-evolution.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apicurio Schema Registry API

Apicurio Registry is a datastore for standard event schemas and API designs. Apicurio Registry enables you to add, update, and remove artifacts from the registry using a REST API interface. It supports Apache Avro, JSON Schema, Protobuf, GraphQL SDL, and more, with configurable compatibility rules including backward, forward, and full compatibility.

- **Human URL:** [https://www.apicur.io/registry/](https://www.apicur.io/registry/)
- **Base URL:** `https://registry.example.com/apis/registry/v2`

#### Tags

- Schema Registry
- Open Source
- Avro
- Compatibility

#### Properties

- [Documentation](https://www.apicur.io/registry/)
- [GitHub Repository](https://github.com/Apicurio/apicurio-registry)
- [Postman Collection](collections/schema-evolution.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schema-evolution.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://docs.confluent.io/platform/current/schema-registry/fundamentals/schema-evolution.html)
- [JSON Schema](json-schema/schema-evolution-change-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/schema-evolution-compatibility-structure.json)
- [J S O N L D Context](json-ld/schema-evolution-context.jsonld)
- [Vocabulary](vocabulary/schema-evolution-vocabulary.yml)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com

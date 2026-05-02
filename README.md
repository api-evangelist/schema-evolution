# Schema Evolution

Schema Evolution is the practice of managing changes to data schemas over time while preserving compatibility between producers and consumers. It covers backward compatibility, forward compatibility, breaking change detection, schema migration strategies, and versioning patterns for REST APIs, event streaming (Kafka/Avro), GraphQL, database schemas, and Protocol Buffers.

**URL:** [https://github.com/api-evangelist/schema-evolution](https://github.com/api-evangelist/schema-evolution)

## Tags

 - Schema Evolution, Backward Compatibility, Forward Compatibility, API Versioning, Breaking Changes, Schema Registry, Data Migration, Kafka

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Confluent Schema Registry API

The Confluent Schema Registry provides a RESTful interface for storing and retrieving your Avro, JSON Schema, and Protobuf schemas with versioned history and configurable compatibility settings.

**Human URL:** [https://docs.confluent.io/platform/current/schema-registry/develop/api.html](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)

#### Tags

 - Schema Registry, Confluent, Kafka, Avro, Compatibility

#### Properties

- [Documentation](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)
- [Reference](https://docs.confluent.io/platform/current/schema-registry/fundamentals/schema-evolution.html)

### AWS Glue Schema Registry API

AWS Glue Schema Registry enables centralized discovery, control, and evolution of data stream schemas with Avro and JSON Schema support.

**Human URL:** [https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html](https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html)

#### Tags

 - AWS, Schema Registry, Cloud, Avro

#### Properties

- [Documentation](https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html)

### Apicurio Schema Registry API

Apicurio Registry is an open-source datastore for standard event schemas and API designs, supporting Avro, JSON Schema, Protobuf, and GraphQL SDL with configurable compatibility rules.

**Human URL:** [https://www.apicur.io/registry/](https://www.apicur.io/registry/)

#### Tags

 - Schema Registry, Open Source, Avro, Compatibility

#### Properties

- [Documentation](https://www.apicur.io/registry/)
- [GitHub Repository](https://github.com/Apicurio/apicurio-registry)

## Common Properties

- [Website](https://docs.confluent.io/platform/current/schema-registry/fundamentals/schema-evolution.html)
- [JSON-LD](json-ld/schema-evolution-context.jsonld)
- [Vocabulary](vocabulary/schema-evolution-vocabulary.yml)

## JSON Schema

| Schema | Description |
|---|---|
| [schema-evolution-change-schema.json](json-schema/schema-evolution-change-schema.json) | Schema representing a single schema change event |

## JSON Structure

| Structure | Description |
|---|---|
| [schema-evolution-compatibility-structure.json](json-structure/schema-evolution-compatibility-structure.json) | Structural documentation for compatibility types and evolution strategies |

## JSON-LD

| Context | Description |
|---|---|
| [schema-evolution-context.jsonld](json-ld/schema-evolution-context.jsonld) | JSON-LD context for schema evolution vocabulary |

## Examples

| Example | Description |
|---|---|
| [schema-evolution-backward-compatible-example.json](examples/schema-evolution-backward-compatible-example.json) | Backward compatible Avro schema change with new optional fields |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [schema-evolution-vocabulary.yml](vocabulary/schema-evolution-vocabulary.yml) | Schema evolution domain terminology and concepts |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com

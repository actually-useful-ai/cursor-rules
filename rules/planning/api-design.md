---
title: API Design
description: "Invoke this rule when designing or reviewing APIs. It provides a comprehensive framework for creating consistent, intuitive, and maintainable APIs that meet both technical and business requirements."
---

# API Design Rule

This rule offers guidance for designing robust, developer-friendly APIs that stand the test of time.

## 1. API Design Principles

Foundational principles for any API:

- **Consistency**: Maintain consistent patterns, naming, and behavior
- **Simplicity**: Design for ease of understanding and implementation
- **Evolvability**: Plan for future changes and extensions
- **Predictability**: Ensure behavior matches developer expectations
- **Domain Alignment**: Reflect business domain concepts in the API design

## 2. Resource Modeling

For REST and resource-oriented APIs:

- **Resource Identification**: Clearly identify core resources and their relationships
- **Noun-Based Resources**: Use nouns, not verbs, for resource names
- **Resource Hierarchy**: Design logical nesting and relationships
- **Collection Patterns**: Use consistent patterns for collections and items
- **Resource State**: Define clear resource lifecycle and state transitions

## 3. Operation Design

For defining available operations:

- **CRUD Mapping**: Map operations to appropriate HTTP methods for REST APIs
- **Idempotency**: Design idempotent operations where appropriate
- **Bulk Operations**: Provide efficient batch operation mechanisms
- **Asynchronous Operations**: Define patterns for long-running operations
- **Action Naming**: Use consistent verb naming for RPC-style operations

## 4. Data Structure Design

For request and response payloads:

- **Schema Definition**: Create clear, documented data schemas
- **Minimal Responses**: Return only necessary data by default
- **Expansion Mechanisms**: Allow clients to request additional related data
- **Consistent Types**: Use consistent data types across the API
- **Pagination Patterns**: Implement standard pagination for large collections

## 5. Error Handling

For predictable error responses:

- **Error Response Structure**: Define consistent error response format
- **Status Codes**: Use appropriate status codes that match semantics
- **Error Types**: Create a taxonomy of error types
- **Actionable Messages**: Provide error messages that suggest resolution
- **Validation Details**: Return detailed validation errors for invalid requests

## 6. Versioning Strategy

For API evolution:

- **Version Indicators**: Define how versions are specified in requests
- **Compatibility Policy**: Document what changes may occur within a version
- **Deprecation Process**: Establish a clear deprecation timeline and notices
- **Migration Support**: Provide tools and guidance for version migrations
- **Version Lifecycle**: Define how long versions will be supported

## 7. Documentation Standards

For API usability:

- **OpenAPI/Swagger**: Maintain machine-readable API specifications
- **Examples**: Provide examples for all operations
- **Use Cases**: Document common implementation patterns
- **SDK Samples**: Include code samples in multiple languages
- **Changelog**: Maintain detailed records of API changes

## 8. Security Considerations

For API protection:

- **Authentication**: Define authentication mechanisms clearly
- **Authorization**: Document permission models and access controls
- **Rate Limiting**: Implement and document usage limitations
- **Input Validation**: Define thorough validation for all inputs
- **Output Filtering**: Ensure sensitive data is properly filtered

## 9. Performance Design

For efficient API usage:

- **Caching Strategy**: Define cache headers and invalidation
- **Compression**: Enable response compression
- **Selective Responses**: Allow clients to request only needed fields
- **Batch Processing**: Support combining multiple operations
- **Monitoring Hooks**: Design for performance monitoring

By following these guidelines, you create APIs that are intuitive to use, adaptable to changing requirements, and maintain a consistent developer experience across your platform. 
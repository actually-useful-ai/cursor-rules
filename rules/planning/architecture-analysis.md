---
title: Architecture Analysis
description: "Invoke this rule when analyzing an existing codebase or planning architectural changes. It provides a framework for systematically understanding code architecture, identifying patterns, and making informed architectural decisions."
---

# Architecture Analysis Rule

This rule provides a structured approach to understanding and evolving software architecture, ensuring changes align with established patterns and best practices.

## 1. Codebase Structure Mapping

Begin by creating a comprehensive map of the codebase:

- **Module Organization**: Identify the major modules/components and their responsibilities
- **Dependency Graph**: Document import/dependency relationships between components
- **Data Flow**: Trace how data moves through the system
- **Control Flow**: Understand the execution patterns and event handling
- **API Boundaries**: Identify internal and external API surfaces

## 2. Pattern Recognition

Identify architectural and design patterns in use:

- **Architectural Patterns**: MVC, MVVM, microservices, event-driven, etc.
- **Design Patterns**: Factory, Singleton, Observer, Strategy, etc.
- **State Management**: How application state is managed and accessed
- **Error Handling**: Patterns for handling exceptions and error states
- **Concurrency Models**: How parallel processing and asynchronous operations are handled

## 3. Technology Stack Analysis

Document the technology ecosystem:

- **Languages & Frameworks**: Primary and auxiliary languages/frameworks
- **Libraries**: Key dependencies and their purposes
- **Database Technologies**: Storage solutions and data access patterns
- **Infrastructure Components**: Servers, services, and cloud resources
- **Build & Deployment Tools**: How code moves from development to production

## 4. Quality Attribute Assessment

Evaluate the architecture against key quality attributes:

- **Performance**: Response time, throughput, and resource utilization
- **Scalability**: Ability to handle increased load or data volume
- **Maintainability**: Code organization, modularity, and documentation
- **Security**: Authentication, authorization, and data protection
- **Accessibility**: Compliance with accessibility standards and practices

## 5. Architectural Decision Framework

When planning changes:

- **Identify Drivers**: Understand the business or technical needs driving changes
- **Consider Alternatives**: Evaluate multiple architectural approaches
- **Document Trade-offs**: Explicitly note advantages and disadvantages of each option
- **Align with Patterns**: Ensure new elements follow established patterns
- **Plan Migration Path**: Create a clear path from current to target architecture

## 6. Architecture Documentation

Maintain living architecture documentation:

- **Component Diagrams**: Visual representations of major system components
- **Sequence Diagrams**: Illustrations of key interactions between components
- **Decision Records**: Documentation of architectural decisions and their rationale
- **Technology Radar**: Tracking of technologies in use and being evaluated
- **Evolution Roadmap**: Planned architectural changes and their timelines

By following this structured approach, you ensure a deep understanding of the existing architecture and make informed decisions that align with established patterns while supporting the system's evolution. 
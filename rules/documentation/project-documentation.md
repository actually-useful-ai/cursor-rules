---
title: Project Documentation
description: "Invoke this rule when implementing changes to ensure comprehensive documentation. It enforces consistent updates to project documentation after each change, preserving existing content while accurately recording all modifications."
---

# Project Documentation Rule

This rule ensures that all project changes are properly documented, creating a comprehensive project history and facilitating collaboration.

## 1. Documentation After Every Change

- Update project documentation after **every single implementation** or change
- Documentation updates should be performed as part of the same commit/task that implements the changes
- Ensure all documentation reflects the current state of the project accurately

## 2. Implementation Documentation

Record all aspects of implemented changes:

- **Features**: Document new functionality with clear usage examples
- **Bug Fixes**: Detail the issue that was fixed and the approach used
- **Refactoring**: Explain architectural improvements and their benefits
- **Performance Optimization**: Note performance gains and measurement metrics
- **Dependencies**: Record new dependencies or version changes

## 3. API Documentation Updates

When modifying APIs, document:

- **Endpoints**: URL paths, HTTP methods, and authentication requirements
- **Request Parameters**: Required and optional parameters with types and formats
- **Response Format**: Structure, status codes, and example responses
- **Error Handling**: Possible error conditions and their responses
- **Version Changes**: API versioning information if applicable

## 4. UI/UX Change Documentation

For user interface changes, document:

- **Navigation Changes**: Updates to user flow and navigation paths
- **Interaction Patterns**: New or modified UI components and how users interact with them
- **Visual Design**: Significant styling changes and their rationale
- **Accessibility**: Accessibility considerations and compliance measures
- **Responsive Behavior**: How the interface adapts to different devices and screen sizes

## 5. Documentation Preservation Rules

- **Never Delete Existing Documentation** unless it is explicitly superseded
- **Use Versioning** when appropriate to track documentation history
- **Cross-Reference** related documentation sections to maintain context
- **Include Migration Notes** when backward compatibility is affected
- **Update All Relevant Documents** to maintain consistency across documentation

## 6. Documentation Format Guidelines

- Use clear, concise language focused on the user's perspective
- Include code examples for technical features
- Add visual aids (diagrams, screenshots) for complex concepts
- Structure documentation hierarchically with proper headings
- Use consistent terminology throughout all documentation

By following these guidelines, you create a comprehensive and up-to-date record of the project's evolution that serves both current and future team members. 
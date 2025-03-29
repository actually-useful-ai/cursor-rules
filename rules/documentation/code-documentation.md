---
title: Code Documentation
description: "Invoke this rule when documenting code or reviewing code documentation. It provides a framework for creating clear, useful documentation that helps developers understand and maintain code effectively."
---

# Code Documentation Rule

This rule outlines best practices for creating effective code documentation that enhances understanding and maintainability.

## 1. Documentation Purpose and Audience

Identify the goals of your documentation:

- **Audience Awareness**: Consider who will read the documentation and their expertise level
- **Usage Context**: Document how and when the code should be used
- **Knowledge Transfer**: Capture insights that aren't obvious from the code alone
- **Rationale Explanation**: Document why decisions were made, not just what they were
- **Future Maintenance**: Write for developers who will maintain the code later

## 2. Code-Level Documentation

For effective in-code documentation:

- **Function Contracts**: Document parameters, return values, exceptions, and side effects
- **Class Responsibility**: Clearly state the purpose and responsibility of each class
- **Implementation Notes**: Explain non-obvious implementation details
- **Algorithm Explanation**: Document complex algorithms and their trade-offs
- **Usage Examples**: Provide simple examples of how to use the code

## 3. Documentation Style

Use consistent documentation patterns:

- **Clear Language**: Use simple, direct language without unnecessary jargon
- **Consistent Style**: Follow a consistent documentation style throughout the codebase
- **Active Voice**: Prefer active voice for clarity ("The function returns..." vs. "A value is returned...")
- **Present Tense**: Use present tense to describe behavior ("The method processes..." not "The method will process...")
- **Standard Format**: Follow language-specific documentation formats (JavaDoc, JSDoc, etc.)

## 4. API Documentation

When documenting APIs:

- **Public Interface Focus**: Thoroughly document all public interfaces
- **Parameter Constraints**: Specify allowed values and constraints on parameters
- **Error Conditions**: Document all possible error conditions and responses
- **Versioning Notes**: Include version information and compatibility notes
- **Authentication Requirements**: Document security and authentication requirements

## 5. Code Examples

Provide effective code examples:

- **Minimal Examples**: Create the simplest possible examples that demonstrate usage
- **Common Use Cases**: Cover the most common usage patterns
- **Edge Cases**: Include examples of handling edge cases and errors
- **Complete Context**: Ensure examples have enough context to understand
- **Runnable Snippets**: Verify that examples actually work as documented

## 6. Documentation Maintenance

Keep documentation current and valuable:

- **Update with Code**: Update documentation alongside code changes
- **Regular Review**: Periodically review documentation for accuracy
- **Deprecation Notices**: Clearly mark deprecated features and provide migration paths
- **Documentation Tests**: When possible, test documentation examples automatically
- **Feedback Incorporation**: Incorporate user feedback to improve clarity

## 7. Visual Documentation Elements

Enhance understanding with visual elements:

- **Diagrams**: Use diagrams to illustrate complex relationships
- **Flowcharts**: Create flowcharts for complex processes and decision trees
- **Architecture Diagrams**: Document system architecture and component interactions
- **Data Flow Diagrams**: Illustrate how data moves through the system
- **State Diagrams**: Document state transitions for stateful components

## 8. Specialized Documentation Types

For specific documentation needs:

- **Troubleshooting Guides**: Create guides for diagnosing and fixing common issues
- **Performance Considerations**: Document performance characteristics and optimization tips
- **Security Guidelines**: Document security considerations and best practices
- **Configuration Options**: Document all configuration options and their effects
- **Extension Points**: Document how to extend or customize functionality

By following these guidelines, you create documentation that enhances the codebase, reduces onboarding time for new developers, and supports long-term maintainability. 
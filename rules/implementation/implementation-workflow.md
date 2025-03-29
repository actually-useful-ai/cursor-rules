---
title: Implementation Workflow
description: "Invoke this rule when planning or implementing changes to a codebase. It provides a systematic approach for analyzing the current structure, mapping component relationships, planning implementation sequence, and ensuring changes maintain existing functionality."
---

# Implementation Workflow Rule

This rule outlines a methodical approach to implementing code changes that preserves functionality while ensuring proper integration with the existing system.

## 1. Systematic Analysis Before Action

Before implementing any changes:

- **Analyze Current Structure**: Understand the architecture and design patterns
- **Identify Dependencies**: Map all components that may be affected by changes
- **Establish Relationships**: Document how components interact with each other
- **Plan Implementation Order**: Create a sequenced plan that minimizes disruption
- **Assess Impact**: Consider how changes might affect performance, usability, and accessibility

## 2. Complete Context Comprehension

When modifying any code:

- **Read Full File Context**: Understand the complete file before making changes
- **Preserve Existing Functionality**: Ensure all current features continue to work
- **Maintain Configuration Options**: Keep all configuration capabilities intact
- **Respect Accessibility Features**: Preserve all accessibility implementations
- **Ensure Responsive Design**: Maintain responsiveness across devices and screen sizes

## 3. Structured Implementation Sequence

Follow this specific order for implementation:

1. **Plan**: Document the intended changes with clear objectives
2. **Structure**: Implement structural and architectural modifications first
3. **Functionality**: Add or modify core functional code
4. **Styling**: Apply styling changes while maintaining accessibility
5. **Testing**: Verify all functionality works as expected
6. **Refinement**: Optimize for performance and edge cases
7. **Documentation**: Update documentation to reflect changes

## 4. Component Hierarchy Integrity

When reorganizing components:

- **Maintain Semantic Structure**: Preserve semantic meaning in component organization
- **Preserve Relationships**: Maintain ARIA relationships and accessibility features
- **Retain Event Handling**: Ensure event propagation works as expected
- **Verify State Management**: Confirm state is properly managed across components
- **Validate Hierarchy**: Test that the new structure doesn't introduce regressions

## 5. Integration Verification

After implementation:

- **Cross-Component Testing**: Test interactions between modified and unmodified components
- **Edge Case Validation**: Verify behavior under unusual or extreme conditions
- **Performance Benchmarking**: Measure performance impact of changes
- **Accessibility Review**: Confirm accessibility standards are maintained
- **Responsive Testing**: Verify proper behavior across different devices and screen sizes

Never proceed to the next implementation step until the current step is fully understood, planned, and properly executed. This methodical approach ensures high-quality, maintainable code that integrates seamlessly with the existing system. 
---
title: Error Handling
description: "Invoke this rule when implementing error handling or debugging error cases. It provides a systematic approach to robust error handling, meaningful error messages, and effective debugging of error conditions."
---

# Error Handling Rule

This rule outlines best practices for implementing comprehensive error handling and debugging error situations in code.

## 1. Error Classification

Categorize errors appropriately:

- **Validation Errors**: Issues with user input or data format
- **Business Logic Errors**: Violations of business rules or constraints
- **System Errors**: Infrastructure, dependency, or environment failures
- **Authentication/Authorization Errors**: Security or permission issues
- **Resource Errors**: Issues with resource availability or access

## 2. Error Handling Patterns

Implement appropriate handling strategies:

- **Try-Catch Blocks**: Surround operations that may throw exceptions
- **Error Objects**: Use structured error objects with relevant metadata
- **Error Boundaries**: Implement component-level error isolation in UI applications
- **Fallback Mechanisms**: Provide graceful degradation when operations fail
- **Retry Logic**: Add automatic retry for transient failures with backoff strategies

## 3. Contextual Error Messages

Create informative error messages:

- **Specificity**: Clearly describe what went wrong
- **Context**: Include relevant operation context in the message
- **Action Guidance**: Suggest potential user actions to resolve the issue
- **Technical Details**: Include technical details for developers (in logs, not user messages)
- **Error Codes**: Use consistent error codes for programmatic handling

## 4. Error Logging

Implement comprehensive error logging:

- **Structured Logging**: Use structured formats for machine parsing
- **Stack Traces**: Include stack traces for debugging context
- **Environment Information**: Log relevant environment and state details
- **Correlation IDs**: Include request IDs to trace errors across system boundaries
- **Sensitive Data Handling**: Ensure sensitive data is not included in logs

## 5. User-Facing Error Presentation

Design user-friendly error experiences:

- **Clear Language**: Use simple, non-technical language for user error messages
- **Appropriate Tone**: Maintain a helpful, not blaming tone
- **Visual Indicators**: Use consistent visual cues for error states
- **Recovery Options**: Provide clear paths to recover from errors
- **Persistent Errors**: Ensure errors remain visible until addressed

## 6. Error Monitoring and Alerting

Set up proactive error detection:

- **Real-time Monitoring**: Implement real-time error tracking
- **Error Rate Alerting**: Alert on sudden increases in error rates
- **Error Aggregation**: Group similar errors to avoid alert fatigue
- **Critical Path Monitoring**: Set lower thresholds for business-critical flows
- **Error Analytics**: Track error trends and patterns over time

## 7. Debugging Error Conditions

Establish effective error debugging techniques:

- **Reproduction Steps**: Document clear steps to reproduce errors
- **Input/Output Logging**: Log inputs and outputs around error points
- **State Snapshots**: Capture application state when errors occur
- **Conditional Debugging**: Add additional logging around suspect code
- **Environment Comparison**: Compare behavior across different environments

## 8. Global Error Handling

Implement system-wide error handling:

- **Uncaught Exception Handlers**: Catch otherwise unhandled errors
- **API Error Interceptors**: Standardize API error responses
- **Graceful Degradation**: Maintain core functionality when non-critical parts fail
- **Health Checks**: Implement comprehensive system health monitoring
- **Circuit Breakers**: Prevent cascading failures with circuit breaker patterns

By following these guidelines, you can create robust applications that handle errors gracefully, providing a better experience for both users and developers. 
---
title: Security Review
description: "Invoke this rule when reviewing code for security vulnerabilities. It provides a systematic approach to identifying common security issues, implementing proper safeguards, and validating protective measures across different application layers."
---

# Security Review Rule

This rule outlines a comprehensive approach to reviewing code for security vulnerabilities and implementing appropriate protections.

## 1. Authentication and Authorization

Review authentication and authorization mechanisms:

- **Authentication Methods**: Verify secure credential handling and storage
- **Password Policies**: Check for strong password requirements and hashing
- **Session Management**: Review session creation, timeout, and invalidation
- **Authorization Checks**: Ensure proper permission verification at all levels
- **Principle of Least Privilege**: Verify users have minimum necessary access

## 2. Data Validation and Sanitization

Ensure proper input handling:

- **Input Validation**: Verify all user input is validated before processing
- **Input Sanitization**: Check for proper escaping of special characters
- **Output Encoding**: Ensure context-appropriate output encoding
- **Parameter Binding**: Use parameterized queries for database operations
- **Content-Type Validation**: Verify file uploads and content types

## 3. Sensitive Data Protection

Protect sensitive information:

- **Data Encryption**: Verify encryption for sensitive data at rest and in transit
- **Key Management**: Review secure handling of encryption keys
- **PII Protection**: Ensure appropriate handling of personally identifiable information
- **Data Minimization**: Collect and retain only necessary data
- **Secure Configuration**: Review handling of credentials in configuration files

## 4. Common Vulnerability Prevention

Check for protection against known vulnerabilities:

- **Injection Attacks**: Verify protection against SQL, NoSQL, OS command injection
- **Cross-Site Scripting (XSS)**: Check for context-aware output encoding
- **Cross-Site Request Forgery (CSRF)**: Verify anti-CSRF token implementation
- **Security Misconfiguration**: Review security headers and server settings
- **Insecure Deserialization**: Check for secure deserialization practices

## 5. API Security

Review API security measures:

- **Authentication**: Verify proper API authentication mechanisms
- **Rate Limiting**: Check for protection against abuse and DoS attacks
- **Input Validation**: Ensure thorough validation of all API parameters
- **Error Handling**: Verify non-revealing error responses
- **CORS Configuration**: Review cross-origin resource sharing settings

## 6. Dependency Security

Evaluate third-party components:

- **Dependency Scanning**: Check for known vulnerabilities in dependencies
- **Version Management**: Verify use of current, supported versions
- **Minimal Dependencies**: Review necessity of all dependencies
- **Supply Chain Security**: Consider the security of package sources
- **License Compliance**: Verify compliance with dependency licenses

## 7. Logging and Monitoring

Review activity tracking:

- **Security Logging**: Verify logging of security-relevant events
- **Log Protection**: Check for protection of log integrity
- **Sensitive Data in Logs**: Ensure sensitive data is not logged
- **Monitoring Integration**: Review hooks for security monitoring systems
- **Alerting Mechanisms**: Check for appropriate security alert triggers

## 8. Security Testing Integration

Recommend security testing approaches:

- **SAST Tools**: Suggest static application security testing tools
- **DAST Approach**: Recommend dynamic testing methodologies
- **Penetration Testing**: Outline areas requiring penetration testing
- **Security Unit Tests**: Suggest security-focused test cases
- **Threat Modeling**: Recommend threat modeling exercises for high-risk areas

By following these guidelines systematically, you can identify security vulnerabilities early in the development process and implement appropriate protections to safeguard applications and data. 
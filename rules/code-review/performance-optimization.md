---
title: Performance Optimization
description: "Invoke this rule when analyzing code for performance issues or implementing optimizations. It provides a structured approach to identifying performance bottlenecks, measuring impact, and implementing targeted improvements."
---

# Performance Optimization Rule

This rule outlines a systematic approach to identifying and resolving performance issues in code.

## 1. Performance Measurement Baseline

Before making any changes:

- **Establish Metrics**: Define clear, measurable performance indicators
- **Create Benchmarks**: Develop reproducible tests that measure current performance
- **Document Environment**: Record hardware, software versions, and testing conditions
- **Capture User Perspective**: Measure metrics that directly impact user experience
- **Automate Tests**: Create scripts for consistent performance measurement

## 2. Bottleneck Identification

Systematically locate performance issues:

- **Profiling**: Use language-appropriate profiling tools to identify hot spots
- **Memory Analysis**: Examine memory usage patterns and potential leaks
- **Network Monitoring**: Analyze API calls, payloads, and request frequency
- **Rendering Performance**: For UI applications, measure rendering times and frame rates
- **Database Operations**: Profile queries, indices, and data access patterns

## 3. Optimization Priority Matrix

Determine which issues to address first:

- **Impact vs. Effort**: Prioritize high-impact, low-effort optimizations
- **Critical Path**: Focus on operations in the main execution path
- **User-Facing Operations**: Prioritize issues directly affecting user experience
- **Resource Constraints**: Address operations consuming constrained resources
- **Frequency**: Target frequently executed code paths

## 4. Implementation Strategy

For each optimization:

- **Single Variable Approach**: Change one thing at a time to measure impact
- **Algorithmic Improvements**: Evaluate algorithm complexity and data structures
- **Caching Strategies**: Implement appropriate caching for expensive operations
- **Lazy Operations**: Defer non-critical operations to improve initial responsiveness
- **Parallelization**: Utilize concurrent operations where appropriate

## 5. Validation and Measurement

After implementing optimizations:

- **Benchmark Comparison**: Compare performance against baseline measurements
- **Regression Testing**: Verify that optimizations don't break existing functionality
- **Resource Utilization**: Confirm improvements in CPU, memory, or network usage
- **Edge Cases**: Test with varying loads and environments
- **User Experience Metrics**: Verify improvements in user-facing performance metrics

## 6. Optimization Documentation

Document all performance work:

- **Techniques Applied**: Record specific optimization approaches used
- **Performance Gains**: Document measurable improvements achieved
- **Trade-offs Made**: Note any compromises in readability or maintainability
- **Future Opportunities**: Identify additional optimization possibilities
- **Monitoring Strategy**: Define ongoing performance monitoring approach

## 7. Common Optimization Techniques

Consider these established optimization patterns:

- **Memoization**: Cache expensive function results
- **Virtualization**: Render only visible content in large lists
- **Bundle Optimization**: Split and lazy-load code bundles
- **Asset Optimization**: Compress and efficiently deliver static assets
- **Request Batching**: Combine multiple API requests where appropriate

By following this structured approach, you can achieve measurable performance improvements while maintaining code quality and functionality. 
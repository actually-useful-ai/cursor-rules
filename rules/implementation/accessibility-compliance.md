---
title: Accessibility Compliance
description: "Invoke this rule when implementing or reviewing UI components to ensure accessibility compliance. It provides comprehensive guidelines for creating accessible interfaces that work for all users, regardless of abilities or assistive technologies."
---

# Accessibility Compliance Rule

This rule ensures that all user interfaces are designed and implemented with accessibility as a core consideration, following established standards and best practices.

## 1. Semantic Structure

Implement proper HTML semantics:

- **Proper Heading Hierarchy**: Use h1-h6 elements in a logical hierarchy
- **Semantic Elements**: Utilize semantic HTML elements (nav, main, section, article, etc.)
- **Landmark Regions**: Define landmark regions for screen reader navigation
- **List Structures**: Use appropriate list elements for lists of items
- **Table Structure**: Include proper headers and captions for data tables

## 2. Keyboard Accessibility

Ensure full keyboard operability:

- **Focus Indicators**: Provide visible focus indicators for all interactive elements
- **Focus Order**: Implement a logical tab order that matches visual layout
- **Keyboard Traps**: Avoid keyboard traps that prevent moving focus away
- **Keyboard Shortcuts**: Document keyboard shortcuts and avoid conflicts
- **Custom Controls**: Ensure custom UI controls can be operated via keyboard

## 3. ARIA Implementation

Use ARIA attributes appropriately:

- **ARIA Roles**: Apply roles only when HTML semantics are insufficient
- **ARIA States**: Keep aria-expanded, aria-checked, etc. synchronized with UI state
- **ARIA Properties**: Use aria-label, aria-labelledby for unlabeled elements
- **Live Regions**: Implement aria-live for dynamic content updates
- **ARIA Landmarks**: Use complementary, main, navigation roles appropriately

## 4. Text Alternatives

Provide alternatives for non-text content:

- **Image Alt Text**: Write descriptive alt text for informative images
- **Decorative Images**: Use alt="" for decorative images
- **Complex Graphics**: Provide detailed descriptions for charts and diagrams
- **Audio/Video**: Include captions, transcripts, and audio descriptions
- **Icon Meaning**: Ensure icons have accessible names or labels

## 5. Color and Contrast

Design with visual accessibility in mind:

- **Color Contrast**: Maintain 4.5:1 contrast ratio for normal text, 3:1 for large text
- **Color Independence**: Never use color alone to convey information
- **Focus Visibility**: Ensure focus indicators have sufficient contrast
- **Text Over Images**: Ensure text over images maintains readable contrast
- **UI Components**: Maintain 3:1 contrast for UI component boundaries

## 6. Forms and Validation

Create accessible forms:

- **Input Labels**: Associate labels with form controls explicitly
- **Input Instructions**: Provide clear instructions for expected input format
- **Error Identification**: Clearly identify errors in form submission
- **Error Suggestions**: Offer suggestions for correcting form errors
- **Fieldset/Legend**: Group related form controls with fieldset and legend

## 7. Dynamic Content

Make dynamic content accessible:

- **Status Messages**: Announce status changes to screen readers
- **Modal Dialogs**: Trap focus within modals while open
- **Content Updates**: Alert screen readers to dynamic content changes
- **Animation Control**: Provide mechanisms to pause or stop animations
- **Auto-updating Content**: Allow users to control auto-updating information

## 8. Testing and Validation

Verify accessibility compliance:

- **Automated Testing**: Use automated tools to check for basic issues
- **Screen Reader Testing**: Test with popular screen readers (NVDA, JAWS, VoiceOver)
- **Keyboard Testing**: Verify all functionality without a mouse
- **Reduced Motion**: Test with reduced motion preferences
- **Zoom/Magnification**: Test at 200% zoom and with screen magnifiers

By following these guidelines, you ensure that your application is usable by the widest possible audience, including people with disabilities, while also improving usability for all users. 
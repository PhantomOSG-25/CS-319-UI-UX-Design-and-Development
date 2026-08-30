# Smart-Home Mobile UX Case Study

## Problem

Smart-home users need quick access to several device types without learning a different interaction model for each one. The prototype explores a single mobile hub that makes common actions visible while keeping deeper controls available when needed.

## Research synthesis

Interview notes emphasized discoverability, direct access to frequently used devices, and confidence that a command was received. These themes informed a dashboard with clear device groupings, dedicated screens for high-attention tasks, and explicit feedback after changes.

## Design decisions

- **Dashboard first:** location, cameras, communication, and smart-plug controls are visible from the home screen.
- **Task-specific screens:** each device type receives controls appropriate to its mental model rather than one generic control panel.
- **Progressive disclosure:** advanced settings stay behind a dedicated path so the primary workflow remains readable.
- **Feedback and status:** device state is shown near the action that changes it, reducing uncertainty.
- **Visual consistency:** repeated navigation and control patterns reduce relearning between screens.

## Accessibility and usability considerations

The next iteration should validate touch-target sizing, contrast in every device state, screen-reader labels, motion reduction, and error recovery for unavailable devices. A moderated usability test should measure time to complete common tasks and whether participants understand device status without additional explanation.

## Scope and limitations

This is a UX prototype, not a production smart-home integration. It does not claim live device connectivity, security hardening, or tested accessibility conformance. The public candidate includes selected prototype evidence; interview photos and original assignment documents remain private until consent and metadata review are complete.

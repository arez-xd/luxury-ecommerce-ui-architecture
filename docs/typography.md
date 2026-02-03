# Typography

Typography in this system is intentionally constrained and product-specific.

The focus is on clarity, consistency, and predictable hierarchy.

## Structure

Typography tokens represent complete text styles rather than atomic fragments.

Each role defines:
- font family
- size
- line height
- weight
- letter spacing

## Line height

Line heights are stored as absolute values.

Percentage-based values from design tools are normalized and rounded to maintain a stable vertical rhythm across platforms.

## Roles

Typography roles are named by function, not appearance.

Examples include:
- `type.h1`
- `type.body`
- `type.caption-1`
- `type.tabbar`

## Non-goals

This system does not attempt to define universal typographic standards or reusable type scales.

# Component Usage

This document describes how components consume design tokens.

It focuses on usage contracts rather than visual specifications.

## Token consumption

Components reference semantic tokens only.

They do not consume core tokens or hardcoded values.

## Responsibility boundaries

- Tokens define values and roles
- Components define layout, structure, and interaction
- States are expressed through semantic token changes

Component implementation details are intentionally not documented here.

## States

Interactive states such as selected or disabled are expressed through dedicated semantic tokens.

Components are responsible for applying the appropriate token based on state.

## Non-goals

This document does not define component APIs, variants, or visual layouts.
Those concerns are handled within the product codebase.

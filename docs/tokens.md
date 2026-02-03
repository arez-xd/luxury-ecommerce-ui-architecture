# Token Architecture

This system uses a two-layer token model:

1. Core tokens
2. Semantic tokens

The separation allows visual changes without breaking component contracts.

## Core tokens

Core tokens define raw primitives such as numeric scales and color values.

They do not encode UI intent and are not consumed directly by components.

## Semantic tokens

Semantic tokens define how values are used in the interface.

They represent roles such as surfaces, text hierarchy, borders, and interaction states.
UI components reference semantic tokens exclusively.


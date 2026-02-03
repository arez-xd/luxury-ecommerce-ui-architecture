# Spacing System

The spacing system defines a small, fixed set of spacing values used across the interface.

It is designed to support consistent layout rhythm while remaining easy to reason about.

## Spacing scale

The system uses a limited spacing scale:

- xs
- sm
- md
- lg
- xl

Each value maps to a fixed numeric step defined in core tokens.

## Usage

Spacing tokens are used for:

- padding
- margin
- gaps between elements

The same spacing tokens apply across these contexts.
Specific placement (e.g. horizontal vs vertical) is defined at the component level.

## Non-goals

The spacing system does not attempt to encode layout rules or responsive behavior.
Those concerns belong to components and layouts.

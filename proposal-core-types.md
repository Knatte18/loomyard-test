# Core domain types

Defines `Task` (the record persisted in `tasks.json`) and the in-memory `Store`.

## Decisions

- `Status` is a nullable string so "unset" differs from empty.
- Field validation happens via a JSON round-trip.

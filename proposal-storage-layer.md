# Storage layer

Loads and saves `tasks.json`, runs dependency and cycle validation, and writes atomically (temp + rename).

## Notes

- Batch upserts validate all entries, then apply all-or-nothing.

# Memory Operations Reference

Standard operating procedures for recording, reconciling, and recalling memory files.

## Storage Hierarchy
Maintain a structured, plain-text memory directory within the workspace:
```plain text
.memory/
├── MEMORY.md              # Compact index with pointers to topic files (< 200 lines)
├── user-preferences.md    # Preferred tools, code styles, and habits
├── project-context.md     # Active architecture and goals
└── corrections.md         # Documented mistakes and prohibited anti-patterns
```

## Atomic Updates & Reconciliation
1. **Reconciliation**: When new instructions contradict older entries, update the entry with the latest timestamp.
2. **Pruning**: Keep `MEMORY.md` under 200 lines by archiving completed sprint milestones into topic files.
3. **Safety**: Never persist plaintext secrets, passwords, or temporary ephemeral paths.

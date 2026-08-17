# Completed Notebooks

This directory will contain separate completed versions of the 2026 Sagan Summer Workshop hands-on notebooks.

## Completion rule

The goal is to preserve the workshop-provided notebook content and add participant work **only where the original notebook explicitly asks the learner to contribute code, values, parameters, or analysis**.

Examples of exercise placeholders include:

```text
TODO
Fill in here
___
```

Existing instructional text and starter code should remain unchanged unless a technical compatibility fix becomes absolutely necessary. Any such exception must be documented explicitly.

## Outputs are part of the completed copy

Where practical, completed notebooks should be saved **with their executed outputs** so readers can see the resulting figures, fitted parameters, diagnostics, tables, and other outputs without rerunning every cell.

This means the repository intentionally keeps both:

- the clean/default workshop template in `../workshop-materials/`; and
- a separate completed copy here containing participant solutions and saved outputs.

The default copy must never be overwritten with the completed one.

## Learning workflow

Learners should ideally:

1. attempt the corresponding workshop exercise first;
2. run and inspect their own results;
3. compare their approach with the completed version here; and
4. consult the notes and result explanations for interpretation.

## Planned organization

```text
completed-notebooks/
├── session-1/
│   ├── 01-microlens-setup.ipynb
│   ├── 02-single-lens-completed.ipynb
│   ├── 03-binary-lens-completed.ipynb
│   └── 04-group-project-completed.ipynb
└── session-2/
    ├── 01-galactic-context-completed.ipynb
    ├── 02-galactic-center-event-completed.ipynb
    ├── 03-dark-lens-completed.ipynb
    ├── 04-sed-fitting-completed.ipynb
    └── 05-binary-event-completed.ipynb
```

## Ownership and third-party content

The repository owner may own participant-authored solutions, notes, documentation, and independently created output material, but that ownership does not extend to the underlying workshop-authored content merely because it is embedded in a completed notebook.

See [`../THIRD_PARTY_NOTICES.md`](../THIRD_PARTY_NOTICES.md) for attribution and rights information concerning the underlying workshop material.

# Android UI framework selection
Use the stack the repo actually uses unless the user explicitly asks for a migration or interop path.

Choose Compose when:
- the repo is already Compose-first
- the screen is new and the project is modernizing around Compose
- state-driven rendering clearly improves maintainability

Choose Views when:
- the repo is predominantly Views/XML-based
- the feature depends on existing Fragments, custom views, adapters, or XML theming infrastructure
- migration cost would exceed the value for the requested change

Use mixed interop only when:
- the repo already does it
- a migration boundary is explicit
- the change can stay localized

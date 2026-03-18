# Flutter performance and release checklist
- Prefer many small widgets and use const where it materially improves rebuild behavior.
- Avoid giant build methods and repeated expensive work.
- Validate adaptive layouts and text scaling.
- Remove placeholder copy, debug traces, and temporary toggles.
- Validate build, tests, and smoke pass for changed flows.
- State whether result is implementation-complete or release-ready.

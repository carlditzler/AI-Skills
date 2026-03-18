# Tauri performance, security, and release checklist
- Keep command payloads narrow and typed
- Avoid chatty frontend-backend round trips
- Prefer batching or local derivation where appropriate
- Validate bundling, config, permissions, capabilities, updater, and window behavior
- Review security exposure before adding plugins, file system access, shell access, or external invocation
- Remove debug prints, placeholder UI, and temporary bypasses
- Confirm build, tests, lint/type checks, and smoke validation on relevant platform targets
- State whether result is implementation-complete or release-ready

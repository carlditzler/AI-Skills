# Tauri architecture and state guidance
Default target:
- thin, typed bridge between frontend and Rust
- clear boundary between UI state, application state, and system side effects
- business logic in Rust or in a dedicated frontend domain layer, not smeared across transport code

Preferred patterns
- Narrow command surface area
- Typed request and response models
- Explicit error mapping between Rust and frontend
- Event/channel use only when command/response is insufficient
- Frontend state model that does not leak transport details into components
- Capability and permission choices that are least-privileged by default

State rules
- Keep window-local UI state local
- Keep shared app state in a deliberate store or repo-standard state layer
- Keep durable state in persistence, not transient in-memory globals unless intentional
- Avoid command explosion and stringly typed event names when a typed interface can be created

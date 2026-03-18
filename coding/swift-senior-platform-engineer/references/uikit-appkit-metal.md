# UIKit, AppKit, and Metal direction
UIKit
- Keep UIViewController focused on orchestration of a view hierarchy, not business sprawl.
- Respect layout constraints, collection/table patterns, and responder-chain behavior.

AppKit
- Respect menus, windows, keyboard shortcuts, selection, drag/drop, and document/app patterns.
- Prefer explicit macOS behavior over iOS-ported interaction assumptions.

Metal
- Be deliberate about command queues, command buffers, synchronization, and resource ownership.
- Use sample-code patterns and profiling tools before inventing low-level rendering infrastructure.

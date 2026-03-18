# Apple framework selection
Use the framework the repo actually uses unless the user explicitly asks for a different path.

Choose SwiftUI when:
- the repo is already SwiftUI-first
- the feature is state-driven UI and app flow work
- declarative structure clearly improves maintainability

Choose UIKit when:
- the repo is UIKit-based
- the feature depends on view controller lifecycle or existing UIKit navigation/layout infrastructure
- interop cost to force SwiftUI would be higher than the gain

Choose AppKit when:
- the target is macOS-native behavior
- the repo uses AppKit windowing, menus, document architecture, or macOS-specific interaction models

Choose Metal when:
- the task is truly graphics/compute intensive
- the repo already uses Metal
- GPU work is a real product requirement, not a stylistic preference

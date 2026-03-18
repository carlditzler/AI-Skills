# Swift / Apple architecture and state guidance
- Keep business logic outside views and controllers where possible.
- Make concurrency ownership explicit.
- Keep rendering state, domain state, and persistence concerns separate.
- Prefer typed models and clear service boundaries.
- Do not create protocol forests or indirection layers without concrete value.
- Mixed SwiftUI/UIKit/AppKit repos should isolate bridges explicitly.

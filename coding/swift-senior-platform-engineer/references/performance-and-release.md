# Swift / Apple performance and release checklist
- Avoid expensive work in SwiftUI body or hot UIKit/AppKit layout paths.
- Watch layout invalidation, render thrash, task duplication, and memory churn.
- Use Instruments/Metal tools when relevant.
- Remove placeholder copy, debug traces, and temporary toggles.
- Validate build, tests, and manual smoke pass for changed flows.
- State whether result is implementation-complete or release-ready.

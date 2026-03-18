# SolidJS guidance for Tauri frontends
Primary docs
- Solid docs: https://docs.solidjs.com/
- Quick start: https://docs.solidjs.com/quick-start
- Intro to reactivity: https://docs.solidjs.com/concepts/intro-to-reactivity
- Stores: https://docs.solidjs.com/concepts/stores
- SolidStart: https://docs.solidjs.com/solid-start

Use when the repo or user selects SolidJS.

Best practices
- Respect fine-grained reactivity and avoid React-style mental models.
- Use signals for local reactive values.
- Use memos for derived values when they reduce work or clarify intent.
- Use stores for structured shared state when justified.
- Keep subscriptions and derivations precise.
- Avoid unnecessary abstractions that obscure reactive flow.

UI and UX quality
- Leverage fine-grained updates to keep UI responsive without flashy noise.
- Make loading and background state obvious but unobtrusive.
- Keep component behavior predictable and interaction latency low.

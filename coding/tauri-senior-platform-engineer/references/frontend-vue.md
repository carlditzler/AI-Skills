# Vue guidance for Tauri frontends
Primary docs
- Vue introduction: https://vuejs.org/guide/introduction.html
- Vue quick start: https://vuejs.org/guide/quick-start
- Component basics: https://vuejs.org/guide/essentials/component-basics
- Tooling: https://vuejs.org/guide/scaling-up/tooling
- Vue style guide: https://vuejs.org/style-guide/

Use when the repo or user selects Vue.

Best practices
- Prefer the Composition API in new code unless the repo standard differs.
- Keep component responsibilities narrow.
- Use SFC structure consistently.
- Keep composables focused and reusable when repetition appears.
- Avoid mixing multiple patterns casually within one feature.
- Follow official style guidance for naming, file organization, and template clarity.

UI and UX quality
- Keep templates readable and state flow easy to trace.
- Make user feedback immediate and legible.
- Preserve keyboard support, semantics, and clear action hierarchy.

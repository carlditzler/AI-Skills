# Svelte guidance for Tauri frontends
Primary docs
- Svelte docs: https://svelte.dev/docs
- Svelte overview: https://svelte.dev/docs/svelte
- Getting started: https://svelte.dev/docs/svelte/getting-started
- Svelte best practices: https://svelte.dev/docs/svelte/best-practices
- SvelteKit intro: https://svelte.dev/docs/kit

Use when the repo or user selects Svelte.

Best practices
- Prefer current Svelte patterns and avoid legacy idioms unless the repo already depends on them.
- Let Svelte's reactive model stay simple; do not over-port React patterns.
- Keep shared state minimal and intentional.
- Use stores only when state truly crosses component boundaries.
- Keep components small and readable.
- Prefer simple reactivity, clear props, and explicit event flow.

UI and UX quality
- Use Svelte's lightweight model to keep interactions fast and crisp.
- Keep transitions purposeful and restrained.
- Avoid hidden state coupling between components.
- Preserve accessibility semantics in generated markup.

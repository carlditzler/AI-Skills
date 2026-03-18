# React guidance for Tauri frontends
Primary docs
- React docs: https://react.dev/
- Quick start: https://react.dev/learn
- Thinking in React: https://react.dev/learn/thinking-in-react
- React reference: https://react.dev/reference/react

Use when the repo or user selects React.

Best practices
- Prefer function components over class components in new code.
- Keep state local until shared ownership is necessary.
- Use effects for synchronization, not as a default escape hatch.
- Model UI as explicit states instead of imperative DOM control.
- Keep presentational components and boundary or data-loading components logically separated.
- Avoid prop drilling only when a cleaner state strategy exists; do not jump to global state prematurely.

UI and UX quality
- Make pending, optimistic, error, and success states explicit.
- Keep forms responsive and precise.
- Minimize jarring rerenders and layout shift.
- Use semantic HTML and strong keyboard/focus behavior.

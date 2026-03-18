# Frontend selection for Tauri
Use one frontend model at a time.

Selection order
1. explicit user choice wins
2. existing repo choice wins
3. package.json, lockfile, Vite config, imports, file extensions, and source layout are evidence
4. if still ambiguous, pick the framework that minimizes change and say so

Common repo clues
- React: jsx/tsx components, react/react-dom, hooks-heavy patterns
- Svelte: .svelte files, @sveltejs packages, SvelteKit or sv tooling
- SolidJS: solid-js imports, signals/memos, SolidStart packages
- Vue: .vue SFCs, vue package, create-vue or Vite Vue plugin

Do not mix component mental models or state patterns across frameworks.

# Compose vs legacy Views guidance
Compose
- Prefer state-driven UI, clear state owners, and Material 3 where it fits the product.

Views
- Respect XML/layout/resource organization, custom view boundaries, and Material Components usage.
- Handle edge-to-edge and insets explicitly.

Mixed repos
- Keep migration boundaries explicit.
- Do not spread Compose into unrelated legacy screens casually.
- Do not back-port a small fix into a large migration unless requested.

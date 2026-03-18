# Release Quality Gates

Use this file as a final gate before treating work as ready for merge or release.

## Definition of done
A change is not release quality unless all applicable items below are true:
- The primary behavior works in the intended user flow.
- Empty, loading, success, and failure states are handled.
- Accessibility basics are covered: labels, focus order, semantics, touch targets, contrast, keyboard support where applicable.
- The change respects platform conventions and existing product patterns.
- Error handling is user-safe and avoids silent failure.
- Logging/telemetry is useful but not noisy, and does not leak sensitive data.
- Tests cover the main risk surface.
- Build, lint, and type checks are clean for the changed surface.
- No known compiler warnings or TODO/FIXME markers are introduced without explicit approval.
- Strings, formatting, theming, and localization readiness are preserved.
- Performance is acceptable for the target interaction.
- Security/privacy posture is unchanged or improved.

## Release gates
### Correctness
- Validate the core path and at least 1 edge/failure path.
- Check state ownership, cancellation, retries, and idempotency where relevant.
- Verify migration or schema changes both forward and failure-safe.

### UX quality
- Primary action is obvious.
- Disabled, pending, success, and error feedback are visible.
- Layout survives dynamic content and common screen/window sizes.
- No clipped text, overlapping controls, or dead-end states.

### Platform fit
- Apple platforms: follow SwiftUI and HIG patterns.
- Android: follow Compose, Material 3, and lifecycle-aware patterns.
- Tauri: frontend/backend boundaries are typed, narrow, and least-privilege.

### Reliability
- Avoid race conditions, duplicate requests, or inconsistent local/cache state.
- Prefer structured concurrency and lifecycle-aware cleanup.
- Do not leave debug code, fake data, or temporary bypasses enabled.

### Observability
- Add logs only where they help debugging or support.
- Use structured error surfaces.
- Avoid sensitive payloads in logs.

### Security and privacy
- Use least-privilege capabilities and permissions.
- Validate external inputs.
- Avoid exposing file system, shell, clipboard, or network access without clear need.
- Do not hardcode secrets, tokens, or private endpoints.

## Final release note format
Report:
- what changed
- what was validated
- what remains risky, if anything
- whether the change is release-ready or only merge-ready

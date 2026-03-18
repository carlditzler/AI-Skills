# Debug Checklist

- Can the bug be reproduced reliably?
- Did a recent change alter ownership, timing, identity, serialization, or configuration?
- Is the data wrong, or is the rendering of correct data wrong?
- Is the bug environment-specific?
- Is there an unhandled error path that silently falls back?
- Could duplicated observers/listeners/tasks explain the behavior?
- What test would have caught this earlier?

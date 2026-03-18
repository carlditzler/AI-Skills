# Performance Checklist

- What user-visible symptom matters most?
- What work repeats unnecessarily?
- Is too much state causing large rerenders/recompositions?
- Is data transformed multiple times across layers?
- Can work move off the hot path or be deferred?
- Are optimizations increasing complexity more than they help?

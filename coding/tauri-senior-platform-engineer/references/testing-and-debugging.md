# Tauri testing and debugging guidance
Testing pyramid
- Unit test Rust domain logic and serialization boundaries
- Unit test frontend state derivation, formatting, and local logic
- Integration test command contracts and high-value persistence/system interactions
- End-to-end test a few core flows only when justified

Debugging workflow
1. Reproduce with exact environment and platform notes
2. Isolate frontend, IPC, Rust, and OS integration boundaries
3. Verify serialization, permissions, capabilities, and path assumptions
4. Instrument the narrowest useful points
5. Fix root cause, then validate both sides of the bridge

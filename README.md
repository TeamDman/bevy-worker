# Bevy Worker

A reusable plugin for the [Bevy](https://bevyengine.org/) game engine that enables running logic in a separate worker thread, communicating with the main game via message passing. This is useful for offloading expensive or blocking computations from the main game loop, such as AI, networking, or interacting with the Windows API.

## Example

See [`examples/simple.rs`](examples/simple.rs) for a minimal usage example

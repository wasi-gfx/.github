# Resources on wasi-gfx from WasmCon 2024

[Link to the slides](wasmcon-wasi-gfx.pdf)

## Examples

* wgpu - [Follow instructions from the windowing-support branch here](https://github.com/wasi-gfx/wgpu/tree/windowing-support/examples-wasi)
* Bevy - Run [this wasm](https://rlt-playground.azureedge.net/public/breakout.wasm) with [graphtime](http://github.com/wasi-gfx/graphtime) on your machine
* ONNX - Run the following command in graphtime: `cargo run --release ./onnx_basic_test_component.wasm` - [wasm file available here](https://rlt-playground.azureedge.net/public/onnx_basic_test_component.wasm)
* Renderlet - open-source examples are [available here](https://github.com/renderlet/wander/), for access to the 3D buildings demo, please contact renderlet directly.

## Get Involved

All contributions are welcome!

### Discuss

Chat about wasi-gfx implementation in the renderlet Discord:

[![Discord Banner 3](https://discordapp.com/api/guilds/1232052216857231443/widget.png?style=banner2)](https://discord.gg/NzmehuETUu)

Join the [Bytecode Alliance Zulip](https://bytecodealliance.zulipchat.com/) to discuss the wasi-gfx spec and more:

### Repositories

* [wasi-webgpu](https://github.com/WebAssembly/wasi-webgpu) - The spec and WIT definition
* [wasi-gfx-runtime](https://github.com/wasi-gfx/wasi-gfx-runtime) - A runtime implementation based on `wgpu`
* [graphtime](https://github.com/wasi-gfx/graphtime) - An example host embedding `wasmtime` for running examples
* [wasi-webgpu-headers](https://github.com/wasi-gfx/wasi-webgpu-headers) - `webgpu.h`-based implementation for C API clientsThe components are here:

### Meetings

The team meets every Tuesday at 17:00-18:00 (5:00-6:00 PM) UTC.

Meetings are open at https://meet.jit.si/moderated/90cbbb56c02272cad4a5d9c48382eb9992de4f691c82e175ead9da4e7d967009

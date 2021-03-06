[![Plop Grizzly](https://plopgrizzly.com/images/logo-bar.png)](https://plopgrizzly.com)

# [Aldaron's System Interface / Vulkan](https://crates.io/crates/asi_vulkan)
Rust safe bindings for Vulkan.

This project is part of [ADI](https://crates.io/crates/adi).

## Features
* Bindings to Vulkan calls on both Unix and Windows
* Safe bindings to some Vulkan calls
* Unsafe bindings to some Vulkan calls

## Roadmap to 1.0 (Future Features)
* All bindings to Vulkan calls are safe
* Bindings match asi\_opengl
* More bindings
* Support Raspberry Pi Direct to display
* Support Android
* Support Nintendo Switch

## Change Log
### 0.8
* Use reference counting in std library instead of ami
* `Vk` is now `Vulkan`

### 0.7
* Use LINEAR REPEATING for textures instead of NEAREST CLAMP

### 0.6
* Use dl\_api crate for dynamic loading.
* Fixed platform-dependant coloration bug.

### 0.5
* Uses sliced triangle fans now.

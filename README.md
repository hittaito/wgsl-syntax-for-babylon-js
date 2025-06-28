# WGSL Syntax for Babylon.js

A Visual Studio Code extension that provides comprehensive syntax highlighting for WGSL (WebGPU Shading Language) with Babylon.js extensions.

## Features

This extension provides full syntax highlighting support for standard WGSL with enhanced support for Babylon.js specific extensions:

### Babylon.js Specific Extensions

- **Special Keywords**: `varying`, `attribute`, `uniform`
- **Preprocessor Directives**: `#include<filename>`
- **Built-in Variables**: `vertexInputs`, `vertexOutputs`, `fragmentInputs`, `fragmentOutputs`, `uniforms`

## Usage

1. Install the extension
2. Open any `.wgsl` file
3. Enjoy comprehensive syntax highlighting optimized for Babylon.js WGSL shaders

## Requirements

- Visual Studio Code 1.101.0 or higher

## Release Notes

### 0.0.1

Initial release featuring:

- Standard WGSL syntax highlighting
- Babylon.js specific keyword support (`varying`, `attribute`, `uniform`)
- Preprocessor directive highlighting (`#include<filename>`)
- Babylon.js built-in variable highlighting (`vertexInputs`, `fragmentOutputs`, etc.)

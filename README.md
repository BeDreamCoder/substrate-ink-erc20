# substrate-ink-erc20

## ink!
ink! is a Rust-based embedded domain specific language (eDSL) for writing Wasm smart contracts specifically for the SRML Contracts module. The main goals of ink! are user friendliness, conciseness, and efficiency.

## Abstraction Layers
The ink! language is composed of three different layers of abstractions with which you can write smart contracts:
- [Lang](https://github.com/paritytech/ink/tree/master/lang): The actual eDSL to provide a user-friendly interface to writing smart contract code.
- [Model](https://github.com/paritytech/ink/tree/master/model): Medium-level abstractions to write smart contracts heavily inspired by [Fleetwood](https://github.com/paritytech/fleetwood).
- [Core](https://github.com/paritytech/ink/tree/master/core): The core utilities and APIs used to interact with the Contracts module.

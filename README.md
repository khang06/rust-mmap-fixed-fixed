rust-mmap-fixed
=========

A Rust library for dealing with memory mapped files, originally extracted from
the Rust standard library source code before it was removed.

## NOTE

This is a fork of the original *rust-mmap* with updated dependencies and a
fix for the Windows version. This exists only because there are no other
alternative crates for `MAP_FIXED` allocations.

See: [memmap-rs#21](https://github.com/danburkert/memmap-rs/issues/21).

## Usage

Add this to your `Cargo.toml`:

```toml
[dependencies]
mmap-fixed = "*"
```

and this to your crate root:

```rust
extern crate mmap_fixed;
```
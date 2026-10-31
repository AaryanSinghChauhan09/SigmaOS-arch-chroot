# SigmaOS arch-chroot

This crate currently contains an empty `no_std` library and a basic arithmetic
test. It does not mount filesystems, enter a chroot, or provide Arch Linux
installation tooling. The test does not exercise chroot behavior.

## Build

```sh
cargo check --lib
```

## License

See [`Cargo.toml`](Cargo.toml).


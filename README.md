# `QEMU on Cortex-M`

This project is derived from Cortex-M-quickstart.
which is developed and maintained by the [Cortex-M team][team].

## Dependencies

``` console
$ rustup target add thumbv6m-none-eabi thumbv7m-none-eabi thumbv7em-none-eabi thumbv7em-none-eabihf
```

``` console
$ tail -n6 .cargo/config
```

4. Build the template application or one of the examples.

``` console
$ cargo build --example hello
```


## License

This template is licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)

- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.


# CS50 Library for Rust

[![](https://img.shields.io/github/v/tag/thechampagne/cs50-rust?label=version)](https://github.com/thechampagne/cs50-rust/releases/latest) [![](https://img.shields.io/github/license/thechampagne/cs50-rust)](https://github.com/thechampagne/cs50-rust/blob/main/LICENSE)


### Download
[Crates](https://crates.io/crates/cs50/)

Add the following line to your Cargo.toml file:

```
cs50 = "1.0.0"
```

### Usage

```rust
fn main() {
    let var_char = cs50::get_char("Prompt: ").unwrap();

    let var_bool = cs50::get_bool("Prompt: ").unwrap();

    let var_i8 = cs50::get_i8("Prompt: ").unwrap();

    let var_i16 = cs50::get_i16("Prompt: ").unwrap();

    let var_i32 = cs50::get_i32("Prompt: ").unwrap();

    let var_i64 = cs50::get_i64("Prompt: ").unwrap();

    let var_i128 = cs50::get_i128("Prompt: ").unwrap();

    let var_u8 = cs50::get_u8("Prompt: ").unwrap();

    let var_u16 = cs50::get_u16("Prompt: ").unwrap();

    let var_u32 = cs50::get_u32("Prompt: ").unwrap();

    let var_u64 = cs50::get_u64("Prompt: ").unwrap();

    let var_u128 = cs50::get_u128("Prompt: ").unwrap();

    let var_f32 = cs50::get_f32("Prompt: ").unwrap();

    let var_f64 = cs50::get_f64("Prompt: ").unwrap();

    let var_isize = cs50::get_isize("Prompt: ").unwrap();

    let var_usize = cs50::get_usize("Prompt: ").unwrap();

    let var_string = cs50::get_string("Prompt: ").unwrap();
}

```

### License

This repo is released under the [MIT](https://github.com/thechampagne/cs50-rust/blob/main/LICENSE).
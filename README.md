# How to use

```bash
$ cd alacritty/alacritty
$ cargo run
```

# Diff

In Alacritty, Cargo.toml:

```
28 ~ │ glutin = { path = "../../glutin/glutin", version = "0.27.0", default-features = false, features = ["serde"] }
```

In Glutin, Cargo.toml:

```
24 ~ │ winit = { path = "../../winit", version = "0.25", default-features = false }
```

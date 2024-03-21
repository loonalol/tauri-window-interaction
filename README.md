# Tauri Window Interaction


Replacement for [Tauri Plugin Window](https://github.com/tauri-apps/tauri-plugin-window) as it is deprecated.

# Usage
-----
`src-tauri/main.rs`
```rust
fn main() {
tauri::Builder::default()
        .plugin(tauri_window_interact::init())
        .run(tauri::generate_context!())
        .expect("error while running tauri application");
}
```

<a href='https://ko-fi.com/L4L8Q0NIF' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

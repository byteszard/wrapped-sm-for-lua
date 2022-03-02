<div align="center">
  <h1><code>Wrapped-SM-For-Lua</code></h1>

  <strong>
  A Rust project using <a href="https://github.com/khvzak/mlua.git">mlua</a> to wrap 
  <a href="https://github.com/bytesboy/Yet-Another-Rust-Implementation-Of-SM-Algorithms.git">Yarism</a> for lua.
  </strong>

</div>

## About

This project is designed to compile [`Yarism`](https://github.com/bytesboy/Yet-Another-Rust-Implementation-Of-SM-Algorithms.git)
to `libwsm4l.so` with [`mlua`](https://github.com/khvzak/mlua.git) for Lua.


## 🚴 Usage

### 🛠️ Build

```
cargo build --release
```

## 🔋 Relative Repositories

* [`Private Repo: Wrapped-SM-For-Lua`](https://github.com/bytesboy/wrapped-sm-for-lua.git): Wrapping `yarism` lib and
  build `libwsm4l.so` for Lua.
* [`Private Repo: LuSM`](https://github.com/bytesboy/lusm): Examples about how to call `libwsm4l.so` lib.
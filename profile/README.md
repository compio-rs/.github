# compio-rs

Welcome to the compio-rs organization! We develop high-performance asynchronous I/O libraries and runtimes for Rust, with a focus on completion-based I/O models like IOCP and io_uring.

## About

compio-rs is dedicated to building modern, efficient, and cross-platform asynchronous runtime solutions for Rust. Our projects leverage completion-based I/O APIs (IOCP on Windows, io_uring on Linux) to provide superior performance while maintaining safety and ease of use.

## Projects

### 🚀 [compio](https://github.com/compio-rs/compio)
A thread-per-core Rust runtime with IOCP/io_uring/polling. This is our flagship project that provides a high-performance asynchronous runtime inspired by monoio.

### 🌐 [cyper](https://github.com/compio-rs/cyper)
An HTTP library based on compio and hyper. Cyper brings the power of completion-based I/O to HTTP clients and servers.

### 🖼️ [winio](https://github.com/compio-rs/winio)
Single-threaded asynchronous GUI runtime. Winio provides an async runtime specifically designed for GUI applications.

### 👀 [see](https://github.com/compio-rs/see)
A high-performance, asynchronous runtime-agnostic alternative to `tokio::sync::watch`.

---

**For more information, visit our [detailed README](https://github.com/compio-rs/.github#readme).**

## Community

- **Telegram:** Join our [Telegram group](https://t.me/compio_rs) for discussions and support
- **Website:** [compio.rs](https://compio.rs)
- **GitHub:** [github.com/compio-rs](https://github.com/compio-rs)

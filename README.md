# compio-rs

Welcome to the compio-rs organization! We develop high-performance asynchronous I/O libraries and runtimes for Rust, with a focus on completion-based I/O models like IOCP and io_uring.

## About

compio-rs is dedicated to building modern, efficient, and cross-platform asynchronous runtime solutions for Rust. Our projects leverage completion-based I/O APIs (IOCP on Windows, io_uring on Linux) to provide superior performance while maintaining safety and ease of use.

## Projects

### 🚀 [compio](https://github.com/compio-rs/compio)
A thread-per-core Rust runtime with IOCP/io_uring/polling. This is our flagship project that provides a high-performance asynchronous runtime inspired by monoio.

**Features:**
- Thread-per-core architecture
- Native support for IOCP (Windows) and io_uring (Linux)
- Cross-platform compatibility with polling fallback
- High-level async APIs for filesystem and network I/O
- MIT licensed

**Website:** [compio.rs](https://compio.rs)

### 🌐 [cyper](https://github.com/compio-rs/cyper)
An HTTP library based on compio and hyper. Cyper brings the power of completion-based I/O to HTTP clients and servers.

**Features:**
- Built on top of compio runtime
- HTTPS support (native-tls and rustls)
- HTTP/2 and HTTP/3 support
- Cookies, charset, multipart, and JSON support
- MIT licensed

### 🖼️ [winio](https://github.com/compio-rs/winio)
Single-threaded asynchronous GUI runtime. Winio provides an async runtime specifically designed for GUI applications.

**Features:**
- Single-threaded design optimized for GUI workloads
- Asynchronous I/O for responsive user interfaces
- MIT licensed

### 👀 [see](https://github.com/compio-rs/see)
A high-performance, asynchronous runtime-agnostic alternative to `tokio::sync::watch`.

**Features:**
- Runtime-agnostic design
- High-performance broadcast channel
- Apache 2.0 licensed

## Community

- **Telegram:** Join our [Telegram group](https://t.me/compio_rs) for discussions and support
- **Website:** [compio.rs](https://compio.rs)
- **GitHub:** [github.com/compio-rs](https://github.com/compio-rs)

## Contributing

We welcome contributions to all our projects! Whether you're just getting started with Rust or are an experienced developer, there are opportunities to contribute at any level. Please check the CONTRIBUTING.md file in each project's repository for specific guidelines.

## License

Most of our projects are licensed under the MIT License. Please check individual project repositories for specific license information.

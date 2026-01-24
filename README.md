# compio-rs

Welcome to the compio-rs organization! We develop compio, an asynchronous runtime for Rust based on completion-based io, along with several related projects.

## Community

- **Telegram:** Join our [Telegram group](https://t.me/compio_rs) for discussions and support
- **Website:** [compio.rs](https://compio.rs)

## Projects

### [compio](https://github.com/compio-rs/compio)
A thread-per-core Rust runtime with IOCP/io_uring/polling. 

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/compio-rs/compio/blob/master/LICENSE)
[![crates.io](https://img.shields.io/crates/v/compio)](https://crates.io/crates/compio)
[![docs.rs](https://img.shields.io/badge/docs.rs-compio-latest)](https://docs.rs/compio)

### [compio-py](https://github.com/compio-rs/compio-py)
**(Proof of Concept)** High-performance Python asyncio alternative event loop powered by compio.

[![Apache-2.0 license](https://img.shields.io/badge/license-Apache--2.0-blue?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAgCAYAAAASYli2AAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAGqSURBVHgBrVbtcYMwDFVy/V82KCMwAp2g2aDtJGSDZoPQDegE0AmSDUwngA1UKYggHBtwyLvTgcF66ONZCcAdQMSMrCEzZHGILzvHZJFaf+AYxxCyTDlmQm5k3cj1EEJ4Qjf085322UI4KrJrCTabTXFDKKmU8uUjWSLvfy2yWixWWbDf16g58tBGadWQsUc/GuZ6Es4YbpGK6ehewI9iLkIMiO7Up7z11AoctcOJyF6pObWOMMJBVy6wmI0rapv9EiGxt3T5nIiOETvePaN99LCTTCL3B0/tfALvYbCTWww4pFJ6HHe4HCXLppVgU0dKP2RvsBwJzESwQ3czfDj0dXRpzODydFkhe+a6nBTqMhPybabCrybSzaUcrVgtSrl2miPhbufqqyn6tWnQN6lxPIGbgHSNi4+FHal1tCDdHt+uh1zDs2ez/VtRy94/soJqVoEPOD4hjdTPrlkKIVANOaJ/VBVzPP2AZelwc2pJ7d2xl2WRw1JC5VQJKc/Ivkm8zkdaWwJ0zLdQbBVZBMOgWE8I3bSpYCU0YUI1OsNK3PPPYZ5QDnoND8A/4kV4DUnNfc8AAAAASUVORK5CYII=)](https://www.apache.org/licenses/LICENSE-2.0)
[![MulanPSL-license](https://img.shields.io/badge/license-MulanPSL--2.0-blue?logo=opensourceinitiative&logoColor=white)](https://license.coscl.org.cn/MulanPSL2/)
[![中文](https://img.shields.io/badge/Zh-中文-success?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAQCAYAAAAWGF8bAAAAAXNSR0IArs4c6QAAAERlWElmTU0AKgAAAAgAAYdpAAQAAAABAAAAGgAAAAAAA6ABAAMAAAABAAEAAKACAAQAAAABAAAAFKADAAQAAAABAAAAEAAAAABHXVY9AAABc0lEQVQ4EaWSOy8EURTHd+wDEY94JVtgg9BI1B6dQqHiE1CrRasT30DpC2hVQimiFkJWVsSj2U1EsmQH4/ff3CO3WDuDk/zmf8/jnntm7qRSMRZFUQ4WYSimNFmaRlsgq8F83K6WuALyva4mixbc+kfJcGqa7CqU4AjaocNpG5oHsx7qB3EqQRC8K4g/gazAMbFTBdbgL1Zh0w2EbnMVHdMrd4LZNotZmIZJKMAemC2z0MS6oDlYhzOQ6c3yGR5Fec4OGPvEHCmn3np+kfyT51+QH8afcbFLTfjgFVS9tZrpwC4v1k9M39w3NTQrBxSM4127SAmNoBt0Ma3QyHRwGUIYdQUh0+c0wZsLPKKH8AwvoHgNlmABZLtwBdqnP0DD9IEG2If6N0oz5SbYSfW4PYhvgNmUxU1JZGEEAsUyjPmB7lhBA1Xe7NMWpuzXa39fnC7lN1b/mZttSNLQv9XXZs2US9LwzjU5R+/d+n/CBx9I2uELeXrRajeDqHwAAAAASUVORK5CYII=)](https://github.com/compio-rs/compio-py/blob/main/README.zh.md)

### [cyper](https://github.com/compio-rs/cyper)
An HTTP library based on compio and hyper. 

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/compio-rs/cyper/blob/master/LICENSE)
[![crates.io](https://img.shields.io/crates/v/cyper)](https://crates.io/crates/cyper)
[![docs.rs](https://img.shields.io/badge/docs.rs-cyper-latest)](https://docs.rs/cyper)

### [winio](https://github.com/compio-rs/winio)
Single-threaded asynchronous GUI runtime. Winio provides an async runtime specifically designed for GUI applications.

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/compio-rs/winio/blob/master/LICENSE)
[![crates.io](https://img.shields.io/crates/v/winio)](https://crates.io/crates/winio)
[![docs.rs](https://img.shields.io/badge/docs.rs-winio-latest)](https://docs.rs/winio)

### [see](https://github.com/compio-rs/see)
An asynchronous runtime-agnostic alternative to `tokio::sync::watch`.

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/compio-rs/see/blob/master/LICENSE%20MIT)
[![APACHE-2.0 licensed](https://img.shields.io/badge/license-APACHE_2.0-blue.svg)](https://github.com/compio-rs/see/blob/master/LICENSE-APACHE%202.0)
[![crates.io](https://img.shields.io/crates/v/see)](https://crates.io/crates/see)
[![docs.rs](https://img.shields.io/badge/docs.rs-see-latest)](https://docs.rs/see)

### [synchrony](https://github.com/compio-rs/synchrony)
A library that provides both sync and unsync versions of common synchronization primitives. 

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/compio-rs/synchrony/blob/master/LICENSE)
[![crates.io](https://img.shields.io/crates/v/synchrony)](https://crates.io/crates/synchrony)
[![docs.rs](https://img.shields.io/badge/docs.rs-synchrony-latest)](https://docs.rs/synchrony)

### [thin-cell](https://github.com/compio-rs/thin-cell)
A compact, single-threaded smart pointer combining reference counting and interior mutability 

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/compio-rs/thin-cell/blob/master/LICENSE)
[![crates.io](https://img.shields.io/crates/v/thin-cell)](https://crates.io/crates/thin-cell)
[![docs.rs](https://img.shields.io/badge/docs.rs-thin--cell-latest)](https://docs.rs/thin-cell)

## Contributing

We welcome contributions to all our projects! Whether you're just getting started with Rust or are an experienced developer, there are opportunities to contribute at any level. Please check the `CONTRIBUTING.md` file in each project's repository for guidelines.

<div align="center">

# 📦 kura-rs

### Rewriting C and C++ in Rust, to end memory-safety bugs. ｜ C / C++ を Rust に書き換えて、メモリ脆弱性をなくす。

![Rust](https://img.shields.io/badge/language-Rust-b7410e?logo=rust&logoColor=white)
![memory safety](https://img.shields.io/badge/goal-memory%20safety-critical)
![hand-written](https://img.shields.io/badge/code-hand--written-2ea44f)
![status](https://img.shields.io/badge/status-early-orange)

**English** ｜ [日本語](https://github.com/kura-rs/.github/blob/main/profile/README.ja.md)

</div>

---

## What is kura-rs?

A project to remove memory-safety vulnerabilities by rewriting widely used C and C++ libraries in Rust.

Buffer overflows, use-after-free and similar bugs keep appearing in C and C++ code. Safe Rust rules out these classes of bugs at compile time, so we port the libraries themselves, one at a time, and show with **evidence** that each port behaves like the original.

## 🧪 Principles

1. **Every line is written by a human.** No LLM-generated code.
2. **Behaviour is checked against the original** with differential tests.
3. **Speed claims come with benchmarks.**
4. **As little `unsafe` as possible.**
5. **Readable code,** so you can review a port before you use it.

## 📚 Ports

| Port | What it is | Status |
| --- | --- | --- |
| [cjson](https://github.com/kura-rs/cjson) | Unofficial Rust port of [DaveGamble/cJSON](https://github.com/DaveGamble/cJSON) | In progress |

## 🤝 Get involved

Questions and corrections are welcome in the Issues of each repository.

---

<div align="center">

Maintained by [@hina-kura49](https://github.com/hina-kura49)

</div>

<div align="center">

# 📦 kura-rs

### C / C++ を Rust に書き換えて、メモリ脆弱性をなくす。 ｜ Rewriting C and C++ in Rust, to end memory-safety bugs.

![Rust](https://img.shields.io/badge/language-Rust-b7410e?logo=rust&logoColor=white)
![memory safety](https://img.shields.io/badge/goal-memory%20safety-critical)
![hand-written](https://img.shields.io/badge/code-hand--written-2ea44f)
![status](https://img.shields.io/badge/status-early-orange)

[English](https://github.com/kura-rs/.github/blob/main/profile/README.md) ｜ **日本語**

</div>

---

## kura-rs とは

広く使われている C / C++ のライブラリを Rust に書き換えて、メモリ脆弱性をなくす活動です。

バッファオーバーフローや解放済みメモリの使用（use-after-free）といったバグは、C / C++ のコードで今も見つかり続けています。`unsafe` を使わない Rust は、こうした種類のバグをコンパイルの時点で防ぎます。そこで、ライブラリそのものを 1 つずつ移植し、元の実装と同じ動きをすることを**根拠**つきで示します。

## 🧪 方針

1. **すべての行を人が書きます。** LLM が生成したコードは入れません。
2. **動作は元の実装と比べて確かめます。** 差分テストを使います。
3. **速いと書くときは、ベンチマークを付けます。**
4. **`unsafe` はできるだけ使いません。**
5. **読みやすく書きます。** 使う前に中身を確かめられるようにします。

## 📚 移植

| 移植 | 内容 | 状態 |
| --- | --- | --- |
| [cjson](https://github.com/kura-rs/cjson) | [DaveGamble/cJSON](https://github.com/DaveGamble/cJSON) の非公式な Rust 移植 | 作成中 |

## 🤝 参加するには

質問や訂正は、各リポジトリの Issues にお寄せください。

---

<div align="center">

管理: [@hina-kura49](https://github.com/hina-kura49)

</div>

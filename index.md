---
layout: default
title: Embedead-Insid
---

# Embedead-Inside.github.io
Embedead-Man 💀

**Embedded & Bare-Metal Development Libraries**

![Embedead-Man.png](https://embedead-inside.github.io/Embedead-Man.png)
<a href="https://github.com">
  <img src="Embedead-Man.png" width="120" height="120" style="border-radius: 50%; object-fit: cover;" alt="Embedead-Man">
</a>


ベアメタルおよび組込みシステム向けに、動的メモリ（`malloc`など）や標準ライブラリ（`libc`）に依存しない、超軽量・スタンドアロン・高移植性なC99ライブラリを開発・公開しています。

---

## 💀 Featured Projects (主要プロジェクト)

組込み開発における利便性とリソースの軽量化を追求した、実践的なライブラリ群です。

### 💀 [embedded-cli](https://github.com/Embedead-Inside/embedded-cli)
**組込み向け超軽量・スレッドセーフなC99コマンドラインインタフェース（CLI）**
- **特長**: 標準ライブラリ（`libc`）非依存、スレッドセーフ、再入可能（リエントラント）な設計。
- **対応**: 20種類以上のマイコン、SoC、およびPC環境に対応。

### 💀 [bare-metal-printf](https://github.com/Embedead-Inside/bare-metal-printf)
**ベアメタル・組込みシステム向けの超軽量・スタンドアロンな `printf` & `snprintf` ライブラリ**
- **特長**: C99準拠。動的メモリを一切使用せず、メモリ制限の厳しいマイコンでも安全に動作。

### 💀 [embedded-uart-retarget](https://github.com/Embedead-Inside/embedded-uart-retarget)
**マルチアーキテクチャ対応 UARTリターゲット（printf/scanf）実装コード集**
- **特長**: 全65種類以上のCPU、MCU、SoC、DSPに対応。Doxygenコメント付きで高い可視性を確保。

### 💀 [tiny-xmodem](https://github.com/Embedead-Inside/tiny-xmodem)
**極小・機種依存なしのXMODEM送受信C言語ライブラリ**
- **特長**: 依存関係ゼロ。シンプルな128バイト/チェックサムに限定した、ベアメタル環境でのブートローダーやデータ転送に最適。

---

## 💀 Design Principles (設計思想)

1. **Zero Dynamic Memory**: 動的メモリを一切使用せず、予期せぬヒープ枯渇やフラグメンテーションを防ぎます。
2. **Hardware Agnostic**: 特定のベンダーやマイコンに依存せず、あらゆるアーキテクチャへシームレスに移植可能です。
3. **No External Dependencies**: 外部ライブラリや標準ライブラリ（`libc`）を必要としない、純粋なスタンドアロンコードを追求します。

---

## 💀 Links
- **GitHub Profile**: [Embedead-Inside (Embedead-Man 💀)](https://github.com/Embedead-Inside)

# ArduBlock Education Edition Style Guide

Version: 0.1

---

# Purpose

This document defines the writing and UI rules used throughout
ArduBlock Education Edition.

Our goal is to make Arduino programming understandable for
children, beginners, teachers, and makers while preserving
technical accuracy.

---

# Design Philosophy

- Education First
- Easy to Read
- Friendly
- Consistent
- Compatible with Arduino terminology

---

# Block Names

Block names should describe what the user wants to do.

Good examples

💡 LEDをつける

🔍 明るさを読む

🖥 OLEDに文字を書く

🎵 音を鳴らす

Bad examples

digitalWrite

PinMode

Output

---

# English API Names

Important Arduino API names should remain visible.

Example

LEDをつける
digitalWrite()

ボタンを読む
digitalRead()

文字を送る
Serial.print()

The English name is for learning purposes.

---

# Naming Rules

Use verbs.

○○する

○○を読む

○○を書く

○○へ送る

○○を表示する

Avoid nouns only.

Bad

LED

Good

LEDをつける

---

# Boolean Blocks

Questions should end with "？"

Examples

ボタンが押された？

LEDがついている？

Wi-Fiにつながった？

---

# Numeric Inputs

Use placeholders.

Good

○秒待つ

○回繰り返す

○番ピン

Bad

5秒待つ

13番ピン

---

# Sensor Blocks

Always use "読む"

Examples

温度を読む

距離を読む

光を読む

---

# Output Blocks

Always use action verbs.

Examples

LEDをつける

LEDを消す

音を鳴らす

画面に表示する

---

# Categories

The standard categories are

🟢 はじめる

🔁 制御

💡 LED

🎮 ボタン・センサー

🖥 表示

🎵 音

⚙ モーター

📡 通信

🧮 数学

📦 変数

🧩 その他

---

# Icons

Icons should be simple and colorful.

Avoid decorative icons that reduce readability.

---

# Japanese

Use natural Japanese.

Avoid direct machine translations.

---

# Goal

Children should understand what a block does
without reading the manual.

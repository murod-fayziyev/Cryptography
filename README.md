# Cryptography

Learning projects in cryptography — interactive, browser-only tools written in plain HTML, CSS and JavaScript (no installation, no dependencies).

## AES Visualizer

Tools for learning how **AES-128** works, round by round and step by step.

**Live demo:** https://murod-fayziyev.github.io/Cryptography/

| Page | What it does |
|---|---|
| [`index.html`](index.html) | Landing page linking to the tools below. |
| [`simple.html`](simple.html) | Encryption **and** decryption of one 16-byte block. All 10 rounds in plain language, with a table of every round. |
| [`steps.html`](steps.html) | Detailed encryption walkthrough: SubBytes, ShiftRows, MixColumns, AddRoundKey and the key schedule, with the actual calculations. |
| [`calculator.html`](calculator.html) | AES-128/192/256 calculator with ECB and CBC modes and PKCS#7 padding. |

The AES implementation is checked against the official test vectors in FIPS-197 (Appendix B and C).

> Educational project. It is not intended to protect real secrets.

---

## O'zbekcha

Kriptografiyani o'rganish bo'yicha loyihalar: brauzerda ishlaydigan interaktiv vositalar (oddiy HTML, CSS va JavaScript, hech narsani o'rnatish shart emas).

**AES Visualizer** — AES-128 shifrlash algoritmini raundma-raund, qadamma-qadam o'rganish uchun:

- `simple.html` — bitta 16 baytli blokni shifrlash va deshifrlash, hamma 10 raund oddiy tilda.
- `steps.html` — shifrlashning batafsil hisob-kitoblari (SubBytes, ShiftRows, MixColumns, AddRoundKey, kalit kengaytirish).
- `calculator.html` — AES-128/192/256 kalkulyatori (ECB va CBC rejimlari).

**Jonli sahifa:** https://murod-fayziyev.github.io/Cryptography/

O'quv maqsadida yaratilgan; haqiqiy sirlarni himoya qilish uchun mo'ljallanmagan.

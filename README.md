![Banner](./banner_sol.png)

# Custom SOL Address Generator ⚡

A fully client-side **Solana vanity address generator**, powered by highly optimized **WebAssembly + SIMD** kernels compiled from C++.
Everything runs directly in your browser — no backend, no key transmission, no trust required.

Generate clean, custom Solana addresses such as:

```
SoL111...
GODx...
KINGx...
based...
alpha...
```

Perfect for **branding**, **identity**, or simply creating a clean and recognizable Solana wallet.

---

## Try it instantly

👉 https://customsoladdress.com

All computation happens client-side using:

- WebAssembly (WASM)
- SIMD acceleration
- Multi-threaded Web Workers
- Highly tuned hashing & ed25519 routines
- Zero backend calls

Private keys never leave your device.

---

## 🔥 Features

- ⚡ WASM-accelerated prefix/suffix brute-force
- 🔐 Keys generated 100% locally
- 🧩 Combined patterns (prefix + suffix) supported
- 🌐 No installation — runs directly in browser
- 🚀 Solana-compatible (ed25519)

---

## Why this exists

Most Solana vanity generators suffer from:

- Slow JavaScript loops
- No SIMD
- No threading
- Poor ed25519 optimization

This project fixes that with:

- WASM-optimized C++ kernels
- Manual SIMD intrinsics
- Web Workers parallelization
- Deterministic in-memory key handling
- Zero-trust architecture

Inspired by **solanity**, but re-engineered for modern browsers and a native-like execution pipeline.

---

## How it works

1. You enter a pattern (ex: SOL, GODX, ALPHA, KING)
2. The WASM engine brute-forces millions of keys per second
3. Once a match is found:
   - Matching Solana address is displayed
   - Private key (generated locally) is shown
4. You save/store the key securely

Everything remains local and ephemeral.

---

## Performance Benchmarks

| Hardware (Browser) | 3-char Prefix | 4-char Prefix | 5-char Prefix |
|-------------------|----------------|----------------|----------------|
| Basic laptop CPU   | slow           | very slow      | impractical    |
| High-end laptop    | decent         | slow           | very slow      |
| Desktop CPU (AVX2) | fast           | manageable     | slow           |
| AVX-512 CPU        | very fast      | fast           | realistic      |

Optimized WASM + SIMD provides multiple-fold speedups over pure JavaScript miners.

---

## 📈 SEO Coverage

Optimized for natural SEO on:

- solana vanity address generator
- client-side solana key generator
- wasm solana vanity tool
- browser solana wallet generator
- ed25519 vanity miner
- solanity inspired generator

---

## 📩 Credits

Inspired by **solanity**.
Live client-side implementation: https://customsoladdress.com

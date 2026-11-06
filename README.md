# chaxus

**I build frontend infrastructure from scratch** — parsers, compilers, component libraries, and WebAssembly. Not gluing libraries together; writing the layers underneath, by hand.

从零手写前端基础设施：解析器、编译器、组件库、WASM。

→ **[chaxus.com](https://chaxus.com)**

---

## Works

| Layer | Repo | What it is |
|---|---|---|
| **Parser** | **[ranlexer](https://github.com/chaxus/ranlexer)** | JavaScript lexer, parser & code generator — a tiny AST toolchain from scratch |
| **Compiler** | **[ranc](https://github.com/chaxus/ranc)** | JSX compiler with a Hooks runtime |
| **Components** | **[ran](https://github.com/chaxus/ran)** · [ran.chaxus.com](https://ran.chaxus.com) | `ranui` (Web Components) + `ranuts` utilities |
| **WASM · Office** | **[document](https://github.com/ranuts/document)** · [edit.chaxus.com](https://edit.chaxus.com) | Full Office suite (docx · xlsx · pptx) in the browser on OnlyOffice WASM — no upload, no backend |
| **WASM · Media** | **[ramedia](https://github.com/chaxus/ramedia)** | ffmpeg brought to the browser via C/C++ → WebAssembly |

Through-line: **parser → compiler → runtime → components → WASM.**

---

## Contributing to

[vite](https://github.com/vitejs/vite) · [prettier](https://github.com/prettier/prettier) · [ai-elements](https://github.com/vercel/ai-elements) · [streamdown](https://github.com/vercel/streamdown)

---

## Stats

![GitHub Metrics](github-metrics.svg)

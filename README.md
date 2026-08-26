<!-- Banner -->
<div align="center">

## 👋 Hi, I'm Noir

<a href="https://github.com/diablo-noir999">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1200&color=C41E3A&center=true&vCenter=true&width=520&lines=building+the+tools+my+agents+wish+they+had;memory+%C2%B7+hooks+%C2%B7+skills+%C2%B7+subagents;if+it+has+an+API%2C+it+has+a+handle" alt="Typing SVG" />
</a>
</div>

---

I'm Noir. Most of my time goes into the scaffolding around coding agents: memory stores, safety hooks, skill packs, editor extensions, the occasional protocol bridge. The models improve every month. The plumbing that keeps them useful and careful mostly doesn't exist yet, so I write it.

Concretely, that's an 18-skill megaplugin for MiMoCode sitting on top of a persistent memory engine (SQLite in WAL mode, hybrid FTS5/BM25 plus TF-IDF search, optional embeddings from a small local ONNX model), a fork of OpenCode called flakecode where those ideas live closer to the core, and Zed extensions for languages other editors forgot. Java and C still show up whenever a mod API or a grammar needs finishing. Rust when I want the compiler to argue with me first.

> *"I trust agents more since I started giving them less room to improvise."*

🔌 agent plumbing &nbsp;·&nbsp; 🧠 memory engines &nbsp;·&nbsp; 🌑 compiling in the dark

---

### 🧠 Currently Thinking About

- Whether persistent memory actually makes an agent better or just louder. Mine can recall a decision from three weeks ago; whether it should bring that up unprompted is a separate question I haven't settled.
- Where guardrails belong when an agent can touch real files: the prompt, the protocol, or the hook that fires before the damage. Leaning toward the last one lately.
- DSLs nobody respects. ZenScript got a finished grammar partly out of spite, and now every half-done tree-sitter grammar I walk past looks like unfinished homework.

---

### 🗡 Things I've Wired

| Project | What it does | Stack |
|---------|-------------|-------|
| **[mimocode-powerpack](https://github.com/diablo-noir999/mimocode-powerpack)** | Megaplugin for MiMoCode: persistent memory with hybrid search, knowledge graph, context analytics, safety and notify hooks, 18 skills, 7 specialized subagents | TypeScript, SQLite |
| **[flakecode](https://github.com/diablo-noir999/flakecode)** | OpenCode fork that pulls frequently-used MiMoCode features into the core, with the powerpack plugin ported along | TypeScript |
| **[zenscript-toolkit](https://github.com/diablo-noir999/zenscript-toolkit)** | Zed extension unifying ZenScript highlighting, Minecraft .lang files, and a bundled LSP for bracket-handler completions | Rust, Tree-sitter |
| **[tree-sitter-zenscript](https://github.com/diablo-noir999/tree-sitter-zenscript)** | Completed ZenScript grammar for tree-sitter; picked up another fork's stubs and finished class declarations, expressions, statements, and types | C |

### ⛏ Earlier Work

The Minecraft MCP bridges that started all this are quieter these days, but they still stand: [jei-mcp](https://github.com/diablo-noir999/jei-mcp) indexes 21K+ items and about 27 million recipe relations offline in SQLite with FTS5, graph traversal included, and [bq-mcp](https://github.com/diablo-noir999/bq-mcp) writes BetterQuesting quest data behind dry-run defaults, backups, and an audit log. Letting a model loose on a questbook taught me some lessons the loud way, and the hooks in everything above carry those scars.

---

### 🛠 Stack & Tools

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java-EA2D2D?style=flat&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)

![MCP](https://img.shields.io/badge/MCP-B22222?style=flat&logo=modelcontextprotocol&logoColor=white)
![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97_HuggingFace-FFCC4D?style=flat)

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-FBF0DF?style=flat&logo=bun&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

![Git](https://img.shields.io/badge/Git-F05033?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-89E051?style=flat&logo=gnubash&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat)
![Zed](https://img.shields.io/badge/Zed-084CCF?style=flat&logo=zedindustries&logoColor=white)

---

### 🔍 Elsewhere in My Forks

Not everything worth reading lives in the table above. There's a mappings-heavy [minecraft-modding-mcp](https://github.com/diablo-noir999/minecraft-modding-mcp) server for digging through decompiled source, a Gemini-behind-Claude-Code proxy in [gemini-for-claude-code](https://github.com/diablo-noir999/gemini-for-claude-code), and a Fossify Gallery fork, which mostly means I use the app daily and like having the source around.

---

### 💼 Open for Collaboration

Interesting problems welcome, especially the ones where somebody warns me "this probably isn't possible." Agent tooling, editor extensions, language servers, mod integrations, cursed save formats, all fair game. If your project deserves a bridge, open an issue on any repo above. I read everything, even when replies take a week.

[![Status](https://img.shields.io/badge/Status-Open_to_Build-8B0000?style=flat-square)](https://github.com/diablo-noir999)
[![Let's Build](https://img.shields.io/badge/%F0%9F%92%AC_Let's_Build_Something-B22222?style=flat-square)](https://github.com/diablo-noir999)

---

## Contact Me

[![GitHub](https://img.shields.io/badge/GitHub-diablo--noir999-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/diablo-noir999)

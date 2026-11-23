# CodeJackRabbit Official 16-Language SDK Suite (`v0.3.4`)

Official 16-language SDK suite, Agent Session Core, MCP Code Mode server, and 2026 agent protocols for CodeJackRabbit (https://api.codejackrabbit.com).

- **Homepage:** https://codejackrabbit.com
- **Base URL:** `https://api.codejackrabbit.com`
- **Generator:** [OmniWrap](https://github.com/JacquesGariepy/omniwrap) (`4b8e6c3e2b4d`)
- **Synchronized:** `2026-11-23T20:37:22Z`

## Dedicated SDK Repositories (16 Languages)

| Language | Tier | Dedicated Repository | OmniWrap Renderer | Install / Usage |
| :--- | :--- | :--- | :--- | :--- |
| **TypeScript** | `core` | [`jackai-dev/codejackrabbit-sdk-typescript`](https://github.com/jackai-dev/codejackrabbit-sdk-typescript) | `typescript` | `npm install @jackai-dev/codejackrabbit-sdk` |
| **JavaScript (ESM)** | `core` | [`jackai-dev/codejackrabbit-sdk-javascript`](https://github.com/jackai-dev/codejackrabbit-sdk-javascript) | `javascript` | `npm install @jackai-dev/codejackrabbit-sdk-js` |
| **Python** | `core` | [`jackai-dev/codejackrabbit-sdk-python`](https://github.com/jackai-dev/codejackrabbit-sdk-python) | `python` | `pip install codejackrabbit-sdk` |
| **Go** | `core` | [`jackai-dev/codejackrabbit-sdk-go`](https://github.com/jackai-dev/codejackrabbit-sdk-go) | `go` | `go get github.com/jackai-dev/codejackrabbit-sdk-go` |
| **Rust** | `core` | [`jackai-dev/codejackrabbit-sdk-rust`](https://github.com/jackai-dev/codejackrabbit-sdk-rust) | `rust` | `cargo add codejackrabbit-sdk` |
| **Java** | `core` | [`jackai-dev/codejackrabbit-sdk-java`](https://github.com/jackai-dev/codejackrabbit-sdk-java) | `java` | `implementation("dev.jackai:codejackrabbit-sdk:0.3.4")` |
| **.NET / C#** | `core` | [`jackai-dev/codejackrabbit-sdk-dotnet`](https://github.com/jackai-dev/codejackrabbit-sdk-dotnet) | `dotnet` | `dotnet add package JackAI.CodeJackRabbit.Sdk` |
| **Kotlin** | `core` | [`jackai-dev/codejackrabbit-sdk-kotlin`](https://github.com/jackai-dev/codejackrabbit-sdk-kotlin) | `kotlin` | `implementation("dev.jackai:codejackrabbit-sdk-kotlin:0.3.4")` |
| **Swift** | `ecosystem` | [`jackai-dev/codejackrabbit-sdk-swift`](https://github.com/jackai-dev/codejackrabbit-sdk-swift) | `swift` | `git clone https://github.com/jackai-dev/codejackrabbit-sdk-swift.git` |
| **Dart** | `ecosystem` | [`jackai-dev/codejackrabbit-sdk-dart`](https://github.com/jackai-dev/codejackrabbit-sdk-dart) | `dart` | `git clone https://github.com/jackai-dev/codejackrabbit-sdk-dart.git` |
| **Ruby** | `ecosystem` | [`jackai-dev/codejackrabbit-sdk-ruby`](https://github.com/jackai-dev/codejackrabbit-sdk-ruby) | `ruby` | `git clone https://github.com/jackai-dev/codejackrabbit-sdk-ruby.git` |
| **PHP** | `ecosystem` | [`jackai-dev/codejackrabbit-sdk-php`](https://github.com/jackai-dev/codejackrabbit-sdk-php) | `php` | `git clone https://github.com/jackai-dev/codejackrabbit-sdk-php.git` |
| **C** | `ecosystem` | [`jackai-dev/codejackrabbit-sdk-c`](https://github.com/jackai-dev/codejackrabbit-sdk-c) | `c` | `git clone https://github.com/jackai-dev/codejackrabbit-sdk-c.git` |
| **C++** | `ecosystem` | [`jackai-dev/codejackrabbit-sdk-cpp`](https://github.com/jackai-dev/codejackrabbit-sdk-cpp) | `cpp` | `git clone https://github.com/jackai-dev/codejackrabbit-sdk-cpp.git` |
| **R** | `ecosystem` | [`jackai-dev/codejackrabbit-sdk-r`](https://github.com/jackai-dev/codejackrabbit-sdk-r) | `r` | `git clone https://github.com/jackai-dev/codejackrabbit-sdk-r.git` |
| **Objective-C** | `ecosystem` | [`jackai-dev/codejackrabbit-sdk-objective-c`](https://github.com/jackai-dev/codejackrabbit-sdk-objective-c) | `objective_c` | `git clone https://github.com/jackai-dev/codejackrabbit-sdk-objective-c.git` |

## Agentic Stack Included Across All Targets

- Unified **Agent Session Core** (`--with-agent-session`) across all 16 languages
- **Agentic Pack** (`SKILL.md`, `AGENTS.md`, `llms.txt`, `.mcp.json`, MCP knowledge server)
- **2026 Agent Protocols** (`agents/protocols`: A2A 1.0 Agent Card, AG-UI SSE events, MCP Tasks state machine)
- **Code Mode MCP Execution** on TypeScript (`typescript-sdk`, zero-dependency Node.js) and Python (`python-sdk`, `code` surface)

## License

Apache-2.0 - Copyright (c) 2026 JackAI.

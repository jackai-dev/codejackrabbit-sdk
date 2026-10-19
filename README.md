# <img src="./favicon.svg" width="28" height="28" alt="CodeJackRabbit" /> CodeJackRabbit Official Polyglot SDKs (`v0.2.0`)

Official multi-language SDKs for **CodeJackRabbit**, automatically generated and synchronized on every release via [OmniWrap](https://github.com/JacquesGariepy/omniwrap).

Whenever a new CodeJackRabbit version is released or OmniWrap adds support for a new target language, the CI/CD pipeline (`sdk-release.yml`) automatically generates the native SDK client, creates the dedicated repository under [`jackai-dev`](https://github.com/orgs/jackai-dev) if needed, and publishes the updated package.

## Dedicated SDK Repositories (8 Languages)

| Language | Dedicated Repository | OmniWrap Renderer | Install / Usage |
| :--- | :--- | :--- | :--- |
| **TypeScript** | [`jackai-dev/codejackrabbit-sdk-typescript`](https://github.com/jackai-dev/codejackrabbit-sdk-typescript) | `typescript` | `npm install @jackai-dev/codejackrabbit-sdk` |
| **JavaScript (ESM)** | [`jackai-dev/codejackrabbit-sdk-javascript`](https://github.com/jackai-dev/codejackrabbit-sdk-javascript) | `javascript` | `npm install @jackai-dev/codejackrabbit-sdk-js` |
| **Python** | [`jackai-dev/codejackrabbit-sdk-python`](https://github.com/jackai-dev/codejackrabbit-sdk-python) | `python` | `pip install codejackrabbit-sdk` |
| **Go** | [`jackai-dev/codejackrabbit-sdk-go`](https://github.com/jackai-dev/codejackrabbit-sdk-go) | `go` | `go get github.com/jackai-dev/codejackrabbit-sdk-go` |
| **Rust** | [`jackai-dev/codejackrabbit-sdk-rust`](https://github.com/jackai-dev/codejackrabbit-sdk-rust) | `rust` | `cargo add codejackrabbit-sdk` |
| **Java** | [`jackai-dev/codejackrabbit-sdk-java`](https://github.com/jackai-dev/codejackrabbit-sdk-java) | `java` | `implementation("dev.jackai:codejackrabbit-sdk:0.2.0")` |
| **.NET / C#** | [`jackai-dev/codejackrabbit-sdk-dotnet`](https://github.com/jackai-dev/codejackrabbit-sdk-dotnet) | `dotnet` | `dotnet add package JackAI.CodeJackRabbit.Sdk` |
| **Kotlin** | [`jackai-dev/codejackrabbit-sdk-kotlin`](https://github.com/jackai-dev/codejackrabbit-sdk-kotlin) | `kotlin` | `implementation("dev.jackai:codejackrabbit-sdk-kotlin:0.2.0")` |

## Automated Synchronization

```bash
# Preview OpenAPI 3.1.0 spec + discovered OmniWrap language plan
npm run sdk:dry-run

# Generate all native SDKs and synchronize with GitHub org jackai-dev
npm run sdk:sync -- --omniwrap-dir /path/to/omniwrap --push
```

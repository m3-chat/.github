# M3 Chat
M3 Chat (or m3-chat) is a 100% open-source and free AI chat web app with no account requirements with 19 models.

## Why use M3 Chat?
Most AI chat web app services are slow, expensive, or require accounts (with heavy message limits). M3 Chat is an open-source, free, no account required, AI chat web app with unlimited messages.
I'm currently running all models on a **Mac Studio M3 Ultra** (which is why it's named **M3** chat :D) using [Ollama](https://ollama.com).

## Models

- [x] LLaMA 3 8B (General Purpose) — `llama3:8b`
- [x] LLaMA 2 (Uncensored) — `llama2-uncensored`
- [x] Gemma 3 (General Purpose) — `gemma3`
- [x] Gemma (General Purpose) — `gemma`
- [x] Phi-3 Mini (Fastest) — `phi3:mini`
- [x] Mistral 7B (Balanced) — `mistral`
- [x] OpenCoder 8B (Code) - `opencoder:8b`
- [x] Gemma 2B (Tiny + Reasonable) — `gemma:2b`
- [x] Gemma 7B (Chat Capable) — `gemma:7b`
- [x] Qwen 1.5 7B (Chat & Reasoning) — `qwen:7b`
- [x] Qwen 2.5 Coder (Code) — `qwen2.5-coder`
- [x] Qwen 3 (General Purpose) — `qwen3`
- [x] DeepSeek Coder 6.7B (Code) — `deepseek-coder:6.7b`
- [x] DeepSeek V2 16B (General Purpose) — `deepseek-v2:16b`
- [x] Dolphin Mistral 7B (Uncensored, Code) — `dolphin-mistral:7b`
- [x] Dolphin 3 8B (General Purpose) — `dolphin3`
- [x] StarCoder2 7B (Coding) — `starcoder2:7b`
- [x] Magistral (Reasoning) — `magistral`
- [x] Devstral (Code) — `devstral`

## Repositories
| Repository | Description | License | Main language |
| --- | --- | --- | --- |
| [frontend](https://github.com/m3-chat/frontend) | Next.js web app for M3 Chat — streaming AI chat interface with a clean, minimal design. | GNU Affero General Public License v3.0 | TypeScript |
| [backend](https://github.com/m3-chat/backend) | Elysia server running Ollama-powered AI models and streaming responses to clients in real-time. | GNU Affero General Public License v3.0 | TypeScript |
| [desktop](https://github.com/m3-chat/desktop) | Cross-platform desktop wrapper for m3-chat, built with Tauri | GNU Affero General Public License v3.0 | Rust |
| [infra](https://github.com/m3-chat/infra) | Deployment and setup scripts for M3 Chat’s frontend and backend. | GNU Affero General Public License v3.0 | Go |
| [status](https://github.com/m3-chat/status) | Fetches status JSON and visualizes 2 weeks of service uptime with color-coded bar charts.  | MIT | TypeScript |
| [tui](https://github.com/m3-chat/tui) | M3 Chat in your terminal! | GNU Affero General Public License v3.0 | C++ |
| [sdk](https://github.com/m3-chat/sdk) | The JavaScript/TypeScript SDK for interacting with the M3 Chat API.  | Apache-2.0 | TypeScript |
| [go-sdk](https://github.com/m3-chat/go-sdk) | The Golang SDK for interacting with the M3 Chat API.  | Apache-2.0 | Go |
| [python-sdk](https://github.com/m3-chat/python-sdk) | The Python SDK for interacting with the M3 Chat API.  | Apache-2.0 | Python |
| [.github](https://github.com/m3-chat/.github) | Welcome to [@m3-chat](https://github.com/m3-chat) 's GitHub ✌️ | MIT | None |
| [discussions](https://github.com/m3-chat/discussions) | Home of @m3-chat 's GitHub discussions | MIT | None |

## Contributing
**m3-chat** is open to contributions, suggestions or any feedback on both backend and frontend repositories.

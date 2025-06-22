# Contributing to M3 Chat

Thank you for your interest in contributing to **M3 Chat** — an open-source, fully free AI chatbot platform. Whether you're fixing bugs, improving documentation, or building new features, your contributions are appreciated!

---

## Repositories

This guide applies to the following repositories:


| Repository | Description | License | Main language |
| --- | --- | --- | --- |
| [frontend](https://github.com/m3-chat/frontend) | Next.js web app for M3 Chat — streaming AI chat interface with a clean, minimal design. | GNU Affero General Public License v3.0 | TypeScript |
| [backend](https://github.com/m3-chat/backend) | DOTNET server running Ollama-powered AI models and streaming responses to clients in real-time. | GNU Affero General Public License v3.0 | C# |
| [desktop](https://github.com/m3-chat/desktop) | Cross-platform desktop wrapper for m3-chat, built with Tauri | GNU Affero General Public License v3.0 | Rust |
| [infra](https://github.com/m3-chat/infra) | Deployment and setup scripts for M3 Chat’s frontend and backend. | GNU Affero General Public License v3.0 | Go |
| [status](https://github.com/m3-chat/status) | Fetches status JSON and visualizes 2 weeks of service uptime with color-coded bar charts.  | MIT | TypeScript |
| [tui](https://github.com/m3-chat/tui) | M3 Chat in your terminal! | GNU Affero General Public License v3.0 | C++ |
| [sdk](https://github.com/m3-chat/sdk) | The JavaScript/TypeScript SDK for interacting with the M3 Chat API.  | Apache-2.0 | TypeScript |
| [go-sdk](https://github.com/m3-chat/go-sdk) | The Golang SDK for interacting with the M3 Chat API.  | Apache-2.0 | Go |
| [python-sdk](https://github.com/m3-chat/python-sdk) | The Python SDK for interacting with the M3 Chat API.  | Apache-2.0 | Python |
| [.github](https://github.com/m3-chat/.github) | Welcome to [@m3-chat](https://github.com/m3-chat) 's GitHub ✌️ | MIT | None |
| [discussions](https://github.com/m3-chat/discussions) | Home of @m3-chat 's GitHub discussions | MIT | None |

---

## Getting Started

1. **Fork** the repository
2. **Clone** your fork:

   ```bash
   git clone https://github.com/<your-username>/<your-fork-repository>
   cd <repository>
    ```

3. **Install dependencies** (example for frontend):

   ```bash
   npm install
   ```

4. **Run the dev server** (example for frontend):

   ```bash
   npm run dev
   ```
   For [backend](https://github.com/m3-chat/backend) it'd be `dotnet run`
---

## Contribution Guidelines

### 1. Open an Issue First

Before sending a pull request, please open an issue on the repository you're working on to:

* Report a bug
* Propose a new feature
* Suggest a refactor or enhancement

This avoids duplicate work and aligns efforts.

### 2. Follow Code Style

* Format with [**Prettier**](https://prettier.io/)
* Use consistent types (e.g. `type` aliases instead of `interface`)
* Use semantic HTML and accessible components where possible

### 3. Write Clear Commits

Use clear, descriptive commit messages like:

* `fix: handle model dropdown overflow`
* `feat: add copy-to-clipboard button`
* `chore(ci): add linux release support`

Follow the [Conventional Commits](https://conventionalcommits.org/) specification.

### 4. Follow the pull request checklist

Before submitting your pull request, please ensure:

- [ ] All code is formatted
- [ ] Linting passes
- [ ] You’ve manually tested your changes
- [ ] Related docs (README / types / JSDoc) are updated
- [ ] You’ve linked the issue this PR addresses (if applicable)

---

## Testing

Be sure to manually test your changes. If you’re contributing to the SDK or backend, unit/integration tests are encouraged.

---

## Code of Conduct

By contributing, you agree to follow our [Code of Conduct](./CODE_OF_CONDUCT.md).

---

## Need Help?

Feel free to open a discussion or ask questions in the issues tab.

Thank you for helping build a better, open, and accessible AI experience!

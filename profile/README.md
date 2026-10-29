### BodhiSearch

**Open-source tools for running AI on your own hardware.**

We build software that lets people run open-weight LLMs locally and lets apps use those models securely, with the user's consent, through standard OpenAI-compatible APIs.

#### Flagship

**[BodhiApp](https://github.com/BodhiSearch/BodhiApp)**: a local AI gateway. It runs LLMs on your machine via llama.cpp, exposes OpenAI-compatible APIs secured with OAuth 2.1, and routes across multiple providers with fallback. It has a Rust core and a TypeScript/React UI, and ships as a desktop app via Tauri. [getbodhi.app](https://getbodhi.app)

#### Build on Bodhi

| Repo | What it is |
|---|---|
| [bodhi-js](https://github.com/BodhiSearch/bodhi-js) | TypeScript SDK that lets web apps and Chrome extensions use a person's local Bodhi |
| [create-bodhi-js](https://github.com/BodhiSearch/create-bodhi-js) | Scaffolder for new Bodhi-powered apps |
| [template-bodhi-react-vite](https://github.com/BodhiSearch/template-bodhi-react-vite) | Vite + React + TypeScript template with Tailwind CSS v4, shadcn/ui and bodhi-js |
| [homebrew-apps](https://github.com/BodhiSearch/homebrew-apps) | Homebrew tap for BodhiSearch apps |

#### Supporting libraries

| Repo | What it is |
|---|---|
| [all-ai-apis](https://github.com/BodhiSearch/all-ai-apis) | Rust request/response types for AI provider APIs |
| [ai-api-types](https://github.com/BodhiSearch/ai-api-types) | TypeScript types for AI provider APIs |

---

Maintained by [Amiruddin Nagri](https://github.com/anagri). To talk about using or contributing to Bodhi, connect on [LinkedIn](https://linkedin.com/in/anagri).
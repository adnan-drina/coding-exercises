# Coding Exercises — AI Code Assistant Demo

Coding exercises for the RHOAI3 Private AI Code Assistant demo. Use the **Continue** extension with a private NVIDIA Nemotron model served via Models-as-a-Service.

## Quick Start

1. Open this workspace in OpenShift Dev Spaces
2. The Continue extension is recommended automatically (`.vscode/extensions.json`)
3. The Continue config template is copied to `~/.continue/config.yaml` on startup
4. Edit `~/.continue/config.yaml`:
   - Replace `YOUR_MAAS_ROUTE` with your MaaS model endpoint (append `/v1`)
   - Replace `YOUR_API_KEY` with your API token from the RHOAI dashboard
5. Select **Local Config** in the Continue sidebar dropdown

## Exercises

Three game exercises in `coding-exercises/game_starters/`:

| Exercise | What to Do |
|----------|-----------|
| `rock_paper_scissors/` | Ask Continue to make it enterprise-grade |
| `simple_quiz/` | Follow the prompts — ask Continue to generate a quiz |
| `word_scramble/` | Follow the prompts — ask Continue to generate a word scramble |

Solutions are in `coding-exercises/game_solutions/`.

## Getting Your MaaS Endpoint and API Key

1. Log in to the RHOAI Dashboard
2. Go to **GenAI Studio > AI asset endpoints**
3. Select your project > **Models as a service** tab
4. Click **View** on the Nemotron model — copy the endpoint URL
5. Click **Generate API token** — copy the token

## References

- [MaaS Code Assistant Quickstart](https://docs.redhat.com/en/learn/ai-quickstarts/rh-maas-code-assistant)
- [Continue — Open-Source AI Code Assistant](https://www.continue.dev/)
- [RHOAI3 Coding Demo](https://github.com/adnan-drina/rhoai3-coding-demo)

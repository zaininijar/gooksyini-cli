# gooksyini-cli

Terminal coding assistant. Agentic loop + tools (read/write files, grep, shell) using free OpenRouter models.

<img src="assets/logo.png" height="120" alt="Gooksyini">

## Run

```bash
git clone https://github.com/zaininijar/gooksyini-cli.git
cd gooksyini-cli
npm i
cp .env.example .env
# set OPENROUTER_API_KEY
npm start
```

Free key: https://openrouter.ai/keys

## Usage

Type a normal request at the prompt, e.g.:

```
read package.json and add a test script
```

Slash commands: `/help`, `/models`, `/model <slug>`, `/current`, `/clear`, `/exit`.

## Tools

`read_file`, `write_file`, `search_file`, `replace_in_file`, `list_directory`, `run_command`.

## Config

Defaults live under `src/config`. Env:

| Var | Required | Description |
|-----|----------|-------------|
| `OPENROUTER_API_KEY` | yes | API key |
| `WORKSPACE_DIR` | no | override agent cwd |

## License

MIT


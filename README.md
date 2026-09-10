# gooksyini-cli

Coding assistant di terminal. Agentic loop + tools (baca/tulis file, grep, shell) lewat model gratis OpenRouter.

<img src="assets/logo.png" height="120" alt="Gooksyini">

## jalanin

```bash
git clone https://github.com/zaininijar/gooksyini-cli.git
cd gooksyini-cli
npm i
cp .env.example .env
# isi OPENROUTER_API_KEY
npm start
```

Key gratis: https://openrouter.ai/keys

## usage

Ketik biasa di prompt, misal:

```
baca package.json dan tambah script test
```

Slash commands: `/help`, `/models`, `/model <slug>`, `/current`, `/clear`, `/exit`.

## tools

`read_file`, `write_file`, `search_file`, `replace_in_file`, `list_directory`, `run_command`.

## config

Default model & limit ada di `src/config` (atau file config di project). Env:

| Var | Wajib | Ket |
|-----|-------|-----|
| `OPENROUTER_API_KEY` | ya | API key |
| `WORKSPACE_DIR` | tidak | override cwd agent |

## license

MIT

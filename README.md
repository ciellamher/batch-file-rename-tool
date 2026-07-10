**batch-file-rename-tool**
A lightweight, robust command-line utility for executing complex bulk file renaming operations using regex and pattern matching.

### 01 — INSTALL

Bash
> git clone https://github.com/ciellamher/batch-file-rename-tool.git
> cd batch-file-rename-tool
> npm install -g .

---

### 02 — USE

> rename-tool --pattern '*.jpg' --replace 'holiday_$$'

Quickly transform thousands of filenames in a target directory with a single command.

---

### 03 — WHAT'S INSIDE

- `index.js` — The main execution script and CLI parser.
- `regex_engine.js` — Pattern matching and string replacement logic.
- `package.json` — Metadata defining the global executable bin command.

---

### 04 — LICENSE

MIT

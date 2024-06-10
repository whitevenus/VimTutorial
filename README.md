# VimTutorial

## Vim Shortcuts

Vim has three mode: `NORMAL`, `INSERT`, `VISUAL`; In the following key-mappings, `n` stands for `NORMAL` mode, `i` stands for `INSERT` mode, `v` stands for `VISUAL` mode.

**Tips**:

- `<CR>`(Carriage Return) stands for `Enter` key。
- `[]` means that it can be omitted.

### Navigation

| Mode | Shortcut    | Description                                   |
| ---- | ----------- | --------------------------------------------- |
| `n`  | `[number]h` | Move left [number times]                      |
| `n`  | `[number]j` | Move down [number times]                      |
| `n`  | `[number]k` | Move up [number times]                        |
| `n`  | `[number]l` | Move right [number times]                     |
| `n`  | `w`         | One word forward to the begining of the word  |
| `n`  | `b`         | One word backward to the begining of the word |
| `n`  | `e`         | Move to the end of the nearest word           |

### Edit in `NORMAL` Mode

| Mode | Shortcut                 | Description                                                     |
| ---- | ------------------------ | --------------------------------------------------------------- |
| `n`  | `:e[dit]` file_name<CR>  | Edit the file                                                   |
| `n`  | `i`                      | Enter `INSERT` mode from `NORMAL` mode and insert before cursor |
| `n`  | `:w[rite]`<CR>           | Write(save) current file                                        |
| `n`  | `:w[rite]` file_name<CR> | Write(save) current file with the file_name                     |
| `n`  | `:q[uit]`<CR>            | Close current file(would fail if you don't save first)          |
| `n`  | `:wq`<CR>                | Save and close current file                                     |
| `n`  | `:q!`<CR>                | Exit current file without saving                                |
| `n`  | `:qa`<CR>                | Exit all file(would fail if you don't save first)               |
| `n`  | `:qa!`<CR>               | Exit all file without saving                                    |
| `n`  | `:wqa`<CR>               | Save and exit all open file                                     |
| `n`  |
| `n`  |
| `n`  |
| `n`  |
| `n`  |
| `n`  |
| `n`  |

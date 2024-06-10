# VimTutorial

## Vim Shortcuts

Vim has three mode: `NORMAL`, `INSERT`, `VISUAL`; In the following key-mappings, `n` stands for `NORMAL` mode, `i` stands for `INSERT` mode, `v` stands for `VISUAL` mode.

**Tips**:

- `<CR>`(Carriage Return) stands for `Enter` key。
- `[]` means that it can be omitted.
- **Narrow word**: A narrow word is a sequence of letters, numbers, and underscores separated by whitespace characters (such as spaces, tabs, or line breaks)
- **Broad word**: A broad word is a sequence of any non-whitespace

### Navigation

| Mode | Shortcut    | Description                                                          |
| ---- | ----------- | -------------------------------------------------------------------- |
| `n`  | `[number]h` | Move left [number times]                                             |
| `n`  | `[number]j` | Move down [number times]                                             |
| `n`  | `[number]k` | Move up [number times]                                               |
| `n`  | `[number]l` | Move right [number times]                                            |
| `n`  | `[number]w` | One narrow word forward to the begining of the word [number times]   |
| `n`  | `[number]b` | One narrow word backward to the begining of the word [number times]  |
| `n`  | `[number]e` | Move forward until the end of the nearest narrow word [number times] |
| `n`  | `[number]W` | One broad word forward to the begining of the word [number times]    |
| `n`  | `[number]B` | One broad word backward to the begining of the word [number times]   |
| `n`  | `[number]E` | Move forward until the end of the nearest broad word [number times]  |

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

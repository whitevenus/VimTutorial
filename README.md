# VimTutorial

## Vim Shortcuts

Vim has three mode: `NORMAL`, `INSERT`, `VISUAL`; In the following key-mappings, `n` stands for `NORMAL` mode, `i` stands for `INSERT` mode, `v` stands for `VISUAL` mode.

**Tips**:

- `<CR>`(Carriage Return) stands for `Enter` key。
- `[]` means that it can be omitted.
- **Narrow word**: A narrow word is a sequence of letters, numbers, and underscores separated by whitespace characters (such as spaces, tabs, or line breaks)
- **Broad word**: A broad word is a sequence of any non-whitespace
- **Paragraph**: A paragraph is the text between any two blank lines

### Open and Close files

| Mode | Shortcut                 | Description                                            |
| ---- | ------------------------ | ------------------------------------------------------ |
| `n`  | `:e[dit]` file_name<CR>  | Edit the file                                          |
| `n`  | `:w[rite]`<CR>           | Write(save) current file                               |
| `n`  | `:w[rite]` file_name<CR> | Write(save) current file with the file_name            |
| `n`  | `:q[uit]`<CR>            | Close current file(would fail if you don't save first) |
| `n`  | `:wq`<CR>                | Save and close current file                            |
| `n`  | `:q!`<CR>                | Exit current file without saving                       |
| `n`  | `:qa`<CR>                | Exit all file(would fail if you don't save first)      |
| `n`  | `:qa!`<CR>               | Exit all file without saving                           |
| `n`  | `:wqa`<CR>               | Save and exit all open file                            |

### Navigation

| Mode     | Shortcut    | Description                                                            |
| -------- | ----------- | ---------------------------------------------------------------------- |
| `n`, `v` | `[number]h` | Move left [number times]                                               |
| `n`, `v` | `[number]j` | Move down [number times]                                               |
| `n`, `v` | `[number]k` | Move up [number times]                                                 |
| `n`, `v` | `[number]l` | Move right [number times]                                              |
| `n`, `v` | `[number]w` | Move a narrow word forward to the begining of the word [number times]  |
| `n`, `v` | `[number]b` | Move a narrow word backward to the begining of the word [number times] |
| `n`, `v` | `[number]e` | Move forward until the end of the nearest narrow word [number times]   |
| `n`, `v` | `[number]W` | Move a broad word forward to the begining of the word [number times]   |
| `n`, `v` | `[number]B` | Move a broad word backward to the begining of the word [number times]  |
| `n`, `v` | `[number]E` | Move forward until the end of the nearest broad word [number times]    |
| `n`, `v` | `[number]{` | Move a paragraph backward [number times]                               |
| `n`, `v` | `[number]}` | Move a paragraph forward [number times]                                |
| `n`, `v` | `[number]E` | Move forward until the end of the nearest broad word [number times]    |
| `n`, `v` | `Ctrl`+`u`  | Move Up half a Page                                                    |
| `n`, `v` | `Ctrl`+`d`  | Move Down half a Page                                                  |
| `n`, `v` | `Ctrl`+`b`  | Move Up a Full Page                                                    |
| `n`, `v` | `Ctrl`+`f`  | Move Down a Full Page                                                  |

### Enter `Insert` Mode from `NORMAL` Mode

| Mode | Shortcut           | Description                                                             |
| ---- | ------------------ | ----------------------------------------------------------------------- |
| `n`  | `i`                | Enter `INSERT` mode from `NORMAL` mode and insert before cursor         |
| `n`  | `cc`               | Delete current line and insert                                          |
| `n`  | `c` + `Navigation` | Delete `Navigation` at cursor and insert, such as `ce`, `c3w`, `c4l`... |

### Edit in `NORMAL` Mode

| Mode | Shortcut                                | Description                                                       |
| ---- | --------------------------------------- | ----------------------------------------------------------------- |
| `n`  | `dd`                                    | Delete(cut) current line                                          |
| `n`  | `d` + `Navigation`                      | Delete(cut) `Navigation` at cursor, similar to `c` + `Navigation` |
| `n`  | `d` + `number` + `d` or `number` + `dd` | Delete(cut) flowing `number` lines                                |
| `n`  | `u`                                     | Undo changes                                                      |
| `n`  | `Ctrl`+`r`                              | Redo changes                                                      |
| `n`  |
| `n`  |
| `n`  |

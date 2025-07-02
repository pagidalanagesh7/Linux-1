# Vi Editor Commands and Shortcuts

Welcome to **Vi**! Below is a handy reference for basic commands, organized by category.

---

## 🔄 Modes in Vi

Vi has different modes:

- **Normal mode** – for navigation and command execution.
- **Insert mode** – for text entry.
- **Visual mode** – for text selection.

### Switching Between Modes

| Command | Description                        |
|---------|------------------------------------|
| `i`     | Insert before the cursor           |
| `I`     | Insert at the beginning of the line|
| `a`     | Append after the cursor            |
| `A`     | Append at the end of the line      |
| `o`     | Open a new line below              |
| `O`     | Open a new line above              |
| `Esc`   | Return to Normal mode              |

---

## 🧭 Navigation Commands (Normal Mode)

| Command | Description                    |
|---------|--------------------------------|
| `h`     | Move left                      |
| `l`     | Move right                     |
| `j`     | Move down                      |
| `k`     | Move up                        |
| `w`     | Next word                      |
| `b`     | Previous word                  |
| `0`     | Start of line                  |
| `^`     | First non-blank character      |
| `$`     | End of line                    |
| `G`     | Go to last line                |
| `gg`    | Go to first line               |
| `:n`    | Go to line number `n`          |

---

## ✍️ Editing Text

| Command  | Description                          |
|----------|--------------------------------------|
| `x`      | Delete character under cursor        |
| `dd`     | Delete current line                  |
| `dw`     | Delete word                          |
| `d$`     | Delete to end of line                |
| `D`      | Same as `d$`                         |
| `yy`     | Yank (copy) current line             |
| `p`      | Paste below                          |
| `P`      | Paste above                          |
| `u`      | Undo                                 |
| `Ctrl + r` | Redo                              |
| `r<char>`| Replace character under cursor       |
| `cw`     | Change word (delete and insert mode) |

---

## 🔍 Search and Replace

| Command            | Description                                      |
|--------------------|--------------------------------------------------|
| `/pattern`         | Search forward for `pattern`                    |
| `?pattern`         | Search backward for `pattern`                   |
| `n`                | Repeat search forward                           |
| `N`                | Repeat search backward                          |
| `:%s/old/new/g`    | Replace all `old` with `new` in file            |
| `:s/old/new/g`     | Replace all `old` with `new` in current line    |

---

## 📄 File Operations

| Command        | Description                   |
|----------------|-------------------------------|
| `:w`           | Save (write) file             |
| `:q`           | Quit                          |
| `:wq` or `ZZ`  | Save and quit                 |
| `:q!`          | Quit without saving           |
| `:e filename`  | Open another file             |
| `:w filename`  | Save as                       |

---

## 📐 Visual Mode

| Command     | Description                        |
|-------------|------------------------------------|
| `v`         | Start character-wise visual mode   |
| `V`         | Line-wise selection                |
| `Ctrl + v`  | Block/column selection             |
| `y`         | Yank selected text                 |
| `d`         | Delete selected text               |
| `>`         | Indent selected                    |
| `<`         | Unindent selected                  |

---

## 💡 Helpful Tips

- `:set number` – Show line numbers
- `:syntax on` – Enable syntax highlighting (Vim)
- `:help` – Open help documentation

---

Happy editing! 🚀

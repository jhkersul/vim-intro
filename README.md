# VIM
### Vi Improved

#### An introduction to the best code editor of all time.
#### Author: Joao Kersul

# Introduction

## Brief History

- **1970s**: Birth of Vi.
    - Vi uses `h`, `j`, `k`, `l` because they didn't have arrow keys back then
- **1990s**: Vim (Vi Improved) by Bram Moolenaar.

## The Vim Advantage

- **Speed & Efficiency**: Edit at the speed of thought.
- **Ubiquity**: Pre-installed on UNIX systems - a remote access boon.
- **Customizability**: Shape it to your needs with a vast plugin ecosystem.

## Why I Chose Vim

- I was 18 years old, when I saw a friend programming
- He was editing a JSON file and converting into objects
- I saw that I was very slow compared to him

# Vim Modes: Mastering Modal Editing

---

## Introduction to Vim Modes

Vim's power stems from its modal editing system. Each mode serves a distinct purpose.

---

## Normal Mode

- The default mode you enter upon opening Vim.
- Used for navigating and manipulating text.
- Commands: 
  - `h`, `j`, `k`, `l` for basic navigation.
  - `w`, `b`, `e` for word-based movement.

---

## Insert Mode

- Directly insert or append text into your document.
- Entering Insert Mode:
  - `i` to insert before the cursor.
  - `a` to append after the cursor.
- Exiting to Normal Mode: `Esc` or `Ctrl` + `[`.


---

## Visual Mode

- For selecting blocks of text.
- Commands:
  - `v` for regular visual mode.
  - `V` to select entire lines.
  - `Ctrl` + `v` for blockwise selection.


---

## Command-line Mode

- Execute Vim commands and search patterns.
- Entered by typing `:` in Normal Mode.
- Examples:
  - `:w` to save (write).
  - `:q` to quit.




# Basic Movement and Editing in Vim

---

## Cursor Movements

Navigate your documents with ease using simple commands.

- **Characters**: `h` (left), `j` (down), `k` (up), `l` (right)
- **Words**: 
  - Forward: `w` (start), `e` (end)
  - Backward: `b` (start)

---

## Jumping Around

Efficiently leap to important locations in your file.

- **Start/End of Line**: `0` and `$`
- **Jump by Line Numbers**: `:` followed by number (e.g., `:10`)

---

## Basic Text Manipulation

Commands that revolutionize your text editing speed.

- **Deleting**:
  - `dd` - Delete a line.
  - `dw` - Delete a word.
- **Copying**:
  - `yy` - Yank (copy) a line.
  - `yw` - Yank a word.
- **Pasting**: 
  - `p` - Paste after cursor.
  - `P` - Paste before cursor.

---

## Changing and Appending Text

Make modifications without entering Insert Mode.

- **Change**:
  - `cw` - Change a word.
  - `cc` - Change an entire line.
- **Append**:
  - `a` - Append after cursor.
  - `A` - Append at end of line.

---

# Powerful Features of Vim

---

## Searching

Quickly locate any piece of text.

- **Forward Search**: `/[search-term]`
- **Backward Search**: `?[search-term]`
- **Repeat Last Search**: `n` (forwards), `N` (backwards)

---

## Replacing

Make multiple substitutions with ease.

- **Replace Globally**: `:%s/[search-term]/[replacement]/g`
- **Replace with Confirmation**: `:%s/[search-term]/[replacement]/gc`

---

## Macros

Automate repetitive tasks by recording and replaying sequences.

- **Start Recording**: `q[any letter]` (e.g., `qa` starts recording to macro "a")
- **Stop Recording**: `q`
- **Playback Macro**: `@[letter]` (e.g., `@a` plays back macro "a")

---

## Splits and Tabs

Work on multiple files or parts of a file simultaneously.

- **Vertical Split**: `:vsp [filename]` or `:vsplit [filename]`
- **Horizontal Split**: `:sp [filename]`
- **Open New Tab**: `:tabnew [filename]`
- **Navigate Tabs**: `gt` (next tab), `gT` (previous tab)

---

## Plugins and Extensibility

Enhance Vim's functionality with plugins.

- **Popular Plugins**: YouCompleteMe (autocomplete), NERDTree (file navigation), Vim-Fugitive (Git integration)
- **Plugin Managers**: Vim-Plug, Dein.vim, Vundle

---

# Thank you


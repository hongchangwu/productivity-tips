# Vim

## Movements
- `h` ←
- `l` →
- `k` ↑
- `j` ↓
- `0` Go to the first character of the line
- `^` Go to the first non-blank charater of the line
- `$` Go to the end of the line
- `gg` Go to the first line
- `G` Go to the last line

## Buffers
- `:e` Reload current bufffer
- `:bd!|e [file]` Open `file` in current buffer
- `:N,Mbd` Delete buffers from `N` to `M`

## Diff mode
- `[c` Jump to the previous conflict
- `]c` Jump to the next conflict
- `:diffg [bufspec]` Copy change from `[bufspec]` the current buffer
- `:diffp [bufspec]` Copy change from the current buffer to `[bufspec]`

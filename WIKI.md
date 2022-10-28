# Using Wiki
This Neovim kickstart uses `lervag/wiki.vim`. Please see its Github page for more information.

# Exporting

## Keys
Essential key mappings are:
- <leader>wp -- exports the current Markdown file to html using Pandoc (`brew install pandoc`).
- <leader>ww -- opens the main Markdown file (`~/wiki/index.md`).

## Export Style
The file `~/wiki/export.css` controls the style of the exported HTML.
My personal CSS is very short, it only tweaks the width of the body as Pandoc's default body width is very narrow.
```css
<style>
body {
  min-width: 80% !important;
}
</style>
```

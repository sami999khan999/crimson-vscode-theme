# Crimson for VS Code

Oxblood almost black, a quiet silver accent; red only where something needs you.

A dark theme made from the Crimson palette of my desktop
([dotfiles](https://github.com/sami999khan999/arch_dotfiles)): the editor, the terminal and the rest of
VS Code in the same colours as the bar, the panels and the terminal around it.

- Backgrounds in near-black oxblood (`#0d0809` side bars, `#140b0d` editor), 1px borders in `#46393b`
- A muted silver-rose accent (`#a0918f`) for focus, the active tab, buttons and badges
- Red (`#e4656b`) kept for errors, deletions and the debugger, so it stands out when it shows
- Desaturated syntax colours: violet keywords, steel-blue functions, sage strings, amber constants,
  copper numbers, slate types
- Terminal ANSI colours that match the desktop's kitty theme
- Semantic highlighting

## Install

From a release `.vsix`:

```sh
code --install-extension crimson-theme-0.1.0.vsix
```

From source:

```sh
git clone https://github.com/sami999khan999/crimson-vscode-theme
cd crimson-vscode-theme
npx @vscode/vsce package
code --install-extension crimson-theme-*.vsix
```

Then pick it: `Ctrl+K Ctrl+T` → **Crimson**.

## Palette

| Role | Colour |
|---|---|
| Side bars, panels | `#0d0809` |
| Editor | `#140b0d` |
| Line highlight | `#1f1a1b` |
| Overlay, selection | `#2d2526` |
| Borders | `#46393b` |
| Text | `#d6d6da` |
| Subtext | `#b4b4b8` |
| Muted | `#796d72` |
| Accent | `#a0918f` |
| Alert | `#e4656b` |
| Green | `#8ea482` |
| Amber | `#c4a46a` |
| Copper | `#c98a5e` |
| Blue | `#8c9bb0` |
| Violet | `#a3889a` |
| Slate | `#8fa9ae` |
| Teal | `#8bb0aa` |

## License

[MIT](LICENSE)

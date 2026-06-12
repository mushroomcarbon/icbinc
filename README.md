# i can't believe it's not Claude markdown preview tool (tnn)

No hassle. No strings attached. Just pure vibes. No handwritten code, just ai slop. Not quality code, just pure slop you can actually slop on. No sentence formats, no good writing - just ai tell after ai tell. 

Tool that displays markdown files like Claude's renderer, with the whole ivory + serif + terracotta stuff. Both available as a standalone HTML file/applet and a .vsix that restyles VS Code's **built-in** markdown preview. It hooks the native preview via `markdown.previewStyles`, so everything works out of the box (thanks vscode!)

## Use

- `Ctrl+Shift+V` (Cmd on mac) — open preview
- `Ctrl+K V` — open preview to the side
- Light/dark follows your VS Code theme automatically.

## Fonts

The preview's CSP blocks remote fonts, so install these locally for the
full effect (free on Google Fonts): **Source Serif 4**, **Inter**, and
optionally **JetBrains Mono**. Falls back to Charter/Georgia otherwise.
If you own actual Tiempos/Styrene, they're already in the font stacks.

## Install from VSIX

```
code --install-extension icbinc-markdown-0.1.0.vsix
```

or Extensions panel → `...` menu → *Install from VSIX...*

## HTML Tool:

Alternatively for if you just want a quick md reader, there's also an HTML version that likewise also works out of the box.

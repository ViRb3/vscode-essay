# VSCode Essay
A [VSCode](https://code.visualstudio.com/) template optimized for HTML and PDF document generation from Markdown with a GitHub-style theme and extras

## Demo
- [PDF](DEMO.pdf)
- [HTML](DEMO.html.zip)
- [Source](DEMO.md)

## Packages
### Required
- [Markdown Converter](https://marketplace.visualstudio.com/items?itemName=manuth.markdown-converter)
  - Used to generate HTML and PDF documents from the VSCode Markdown Preview screen
### Optional
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  - Provides useful keyboard shortcuts, tab completions and more
- [Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)
  - Used to add Mermaid capabilities
- [Markdown+Math](https://marketplace.visualstudio.com/items?itemName=goessner.mdmath)
  - Used to add KaTeX (LaTeX math) capabilities

## Usage
1. Clone this repo
2. Open the directory with `VSCode`
3. Install the required (and optional) packages
4. Press `F1 > Markdown Convert Document`

## Customization
- `/assets/github-markdown.css`
  - base theme from [github-markdown-css](https://github.com/sindresorhus/github-markdown-css) (MIT License)
- `/assets/fixes.css`
  - VSCode-specific fixes from [vscode-github-markdown-preview-style](https://github.com/mjbvz/vscode-github-markdown-preview-style)  (MIT License) and personal patches
- `/assets/style.css`
  - extra style changes

## License
MIT
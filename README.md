# AsciiDoc support for VSCode

[![Version](https://vsmarketplacebadge.apphb.com/version/joaompinto.vscode-asciidoctor.svg)](https://marketplace.visualstudio.com/items?itemName=joaompinto.vscode-asciidoctor)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/joaompinto.vscode-asciidoctor.svg)](https://marketplace.visualstudio.com/items?itemName=joaompinto.vscode-asciidoctor)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/joaompinto.vscode-asciidoctor.svg)](https://vsmarketplacebadge.apphb.com/rating/joaompinto.vscode-asciidoctor.svg)

A vscode support extension that provides live preview, syntax highlighting and symbols for the AsciiDoc format.

The extension can be activated in two ways

* Toggle Preview - `ctrl+shift+v` (Mac: `cmd+shift+v`)
* Open Preview to the Side - `ctrl+k v` (Mac: `cmd+k v`)
* View symbols - go to symbol action - `ctrl+shift+o`, select a heading.

## How to install

    ext install joaompinto.vscode-asciidoctor

## Demo

## Optional

If you want to use the Ruby version of [**Asciidoctor**](http://asciidoctor.org/docs/install-toolchain/ ) you need to change the AsciiDoc.use_asciidoctor_js setting to _false_.

## How to build and install from source (Linux)

```bash
git clone https://github.com/joaompinto/vscode-asciidoctor
cd vscode-asciidoctor
npm install
sudo npm install -g vsce
vsce package
code --install-extension *.vsix
```

## Credits

This extension is based on [VS Code markdown extenstion](https://github.com/Microsoft/vscode/tree/79b44aa704ce542d8ca4a3cc44cfca566e7720f1/extensions/markdown)

The render engine uses [Asciidoctor](https://asciidoctor.org/docs/asciidoctor.js/).

The symbol support is based on <https://github.com/jrieken/md-navigate>

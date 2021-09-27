# Mermaid language support in Atom
Adds syntax highlighting to [Mermaid](https://mermaid-js.github.io/mermaid/#/) files in [Atom](https://atom.io/).

Example mermaid diagram:
```
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
How it should look with syntax highlighting:
![example of syntax highlighting](/resources/example.PNG)

## Mermaid rendering in Atom
Several packages render mermaid drawings. None of these include syntax highlighting for Mermaid.
* [atom-mermaid](https://atom.io/packages/atom-mermaid) (mermaid files)
* [markdown-preview-enhanced](https://atom.io/packages/markdown-preview-enhanced) (inside of markdown)
* [markdown-preview-plus](https://atom.io/packages/markdown-preview-plus) (inside of markdown)
* [markdown-preview](https://atom.io/packages/markdown-preview) (inside of markdown)

## Mermaid syntax highlighting within markdown
See issue [mermaid syntax in code blocks](https://github.com/ytisf/language-mermaid/issues/2).
* The popular package [language-markdown](https://github.com/burodepeper/language-markdown) has support for mermaid.

## Install
Install the package language-mermaid in the Atom package manager UI or in your shell:
```
apm install language-mermaid
```

## Contribute
The grammar rules are not complete. Contributions are greatly appreciated. If you see something that is incorrect or needs adding please fork this repository and open a pull request or open an issue and report it.

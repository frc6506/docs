# Contributing

## Issues

Check out the issues list

## Pull Requests

## Spellcheck

![Spellcheck Action](https://github.com/frc6506/docs/workflows/Spellcheck%20Action/badge.svg)

An automatic spell checker runs as a GitHub Action.  Note that at this time, there are no other writing inspectors used.  Although slightly finicky, the VS Code extension [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) can help to catch misspelled words.

### Word Whitelist

The word white list is located at `.github/workflows/config/.wordList.txt`.  Please keep it neatly formatted in alphabetical order.  The VS Code extension [Permute Lines](https://marketplace.visualstudio.com/items?itemName=earshinov.permute-lines) adds the command `Sort Lines Ascending` to the Commands Pallet ([Crtl] + [Shift] + [P]) for easier sorting.

## Markdown

[![Markdown Linter](https://github.com/frc6506/docs/actions/workflows/markdownwonLinter.yml/badge.svg)](https://github.com/frc6506/docs/actions/workflows/markdownwonLinter.yml)
An automatic markdown linter inspects the all markdown files.  You can use the VS Code extension [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) to help you out in VS Code.

Also checkout the VS Code extension [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) for live preview in VS Code.

### Rules

[Rules List](https://github.com/DavidAnson/markdownlint/blob/main/doc/Rules.md})

### Ignored Rules

MD033 - Ban on Inline HTML.  Inline HTML is permitted were necessary.

## Compress Images

![Compress Images](https://github.com/frc6506/docs/workflows/Compress%20Images/badge.svg)
Nonprofits get free space, but the compress images action should be running anyways.

[Site Index](https://frc6506.github.io/docs/index)

<br>
_Updated 20210415T1905 PDT_
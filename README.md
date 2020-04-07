# Clinical Medicine Notes

## Installation

```bash
pip install "mkdocs-material>=5.0.0rc4"
pip install mkdocs-git-revision-date-localized-plugin
pip install mkdocs-awesome-pages-plugin
```

Serving the site at <http://localhost:8000> either by running at the terminal
```bash
mkdocs serve
```
or running the task in VSCode using <kbd>command</kbd> + <kbd>shift</kbd> + <kbd>P</kbd> and select **Task: Run Task** and choose the `mkdocs serve` option. These tasks are defined in `.vscode/tasks.json`. 

## Migrating from LaTeX
Use `pandoc` to convert latex to markdown and disable wrapping at a specific column
```bash
pandoc --wrap=none -o output.md input.tex
```
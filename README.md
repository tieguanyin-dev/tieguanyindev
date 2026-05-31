## Tieguanyin Tea Website

This repository contains a Hugo website built with the **hello-coolapso** template.

The site includes content about:
- tea culture
- Guanyin (the Bodhisattva of Compassion)
- how Tieguanyin tea came about

### Run locally

```bash
hugo server
```

### Build

```bash
hugo
```

### GitHub Pages

A GitHub Actions workflow is included to publish the Hugo site to GitHub Pages.

Live URL:
- https://tieguanyin-dev.github.io/tieguanyindev/

Important:
- https://tieguanyin-dev.github.io/ is the account root, not this project path.
- The theme is included in this repo at `themes/hello-coolapso` and is selected in `config.toml` with `theme = "hello-coolapso"`.

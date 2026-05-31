## Tieguanyin Tea Website

This repository contains a Hugo website built with the **hello-4s3ti** template.

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
- The official theme is included as a git submodule at `themes/hello-4s3ti` and selected in `config.toml` with `theme = "hello-4s3ti"`.

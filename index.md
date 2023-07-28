---
title: "Minimal Example of Tutorial in Pandoc Markdown"
author: Raniere Silva
image: img/cover.jpg
image-alt: Individual letter stamp in metal box.
bibliography: references.bib
---

This example illustrates the **required** metadata by [`andrew`](https://github.com/GESIS-Methods-Hub/andrew) for a tutorial written as a Pandoc Markdown, an extension to Markdown [@markdown2004].

GitHub renders `.md` files as [GitHub Flavored Markdown](https://github.github.com/gfm/) and, because of it, some elements will not be correct display on GitHub.

Although footnotes are supported, the use of footnotes is discouraged[^1].

[^1]: Because of it makes navigation harder.

Math can be written using [LaTeX](https://www.latex-project.org/) and is render by [MathJax](https://www.mathjax.org/). Both inline, for example $x$, and display, for example $$x = \sqrt{a^2 + b^2}\text{,}$$ is supported.

## Binder

The link to Binder will launch the default [JupyterLab IDE](https://jupyterlab.readthedocs.io/).

## References

::: {#refs}
:::
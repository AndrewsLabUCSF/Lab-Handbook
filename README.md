# Andrews Lab Handbook

Visit the [published handbook](https://andrewslabucsf.github.io/Lab-Handbook/).

## Build locally

Install [Quarto](https://quarto.org/docs/get-started/) and run the following command from the repository root:

```bash
quarto preview
```

To rebuild the HTML site, PDF, and EPUB in `docs/`, run:

```bash
quarto render
```

GitHub Pages publishes the contents of `docs/` from the `main` branch. Commit the source changes and regenerated `docs/` files together so that the published handbook remains synchronized with its source.

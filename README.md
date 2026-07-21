# World Model Benchmarks organization website

This repository publishes the organization-level GitHub Pages site at:

https://world-model-benchmarks.github.io/

The website source is maintained in [`World-Model-Benchmarks/World-Model-Benchmarks`](https://github.com/World-Model-Benchmarks/World-Model-Benchmarks), under the `docs/` directory. The deployment workflow in this repository checks out that source, rewrites site-level URLs for the organization root domain, and deploys the resulting static site through GitHub Pages.

## Updating the website

Edit the website source in the main survey repository:

- `World-Model-Benchmarks/World-Model-Benchmarks/docs/`

This publishing repository synchronizes automatically every hour. A deployment can also be started manually from **Actions → Deploy organization website → Run workflow**.

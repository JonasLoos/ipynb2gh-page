# ipynb2gh-page

Display a jupyter notebook using github pages. Just copy the [action](/.github/workflows/deploy-ipynb-page.yml) or use this repo as a template.

## Setup

Make sure to set `Settings -> Actions -> General -> Workflow permissions` to `Read and write permissions` before the GitHub Action is run. After that, enable GitHub Pages in `Settings -> Pages` by setting the Source branch to `gh-pages`.

You can adjust the notebook name to use and further settings in the action itself: [`.github/workflows/deploy-ipynb-page.yml`](/.github/workflows/deploy-ipynb-page.yml).

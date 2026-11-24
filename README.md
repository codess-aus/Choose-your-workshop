# Choose your workshop

A single-page [workshop chooser](https://codess-aus.github.io/Choose-your-workshop/) built with MkDocs. Edit `docs/index.md` to update the workshop list.

## Preview locally

With Python 3.12, run these commands from the repository root:

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
mkdocs serve
```

Open <http://127.0.0.1:8000/Choose-your-workshop/> to preview the page. Run `mkdocs build --strict` to check the build or generate static files in `site/`.

## Publish on GitHub Pages

In the repository, go to **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**. The **MkDocs site** workflow checks builds on pull requests and publishes the site when changes land on `main`. To deploy manually after enabling Pages, run **MkDocs site** from the **Actions** tab and select `main`.
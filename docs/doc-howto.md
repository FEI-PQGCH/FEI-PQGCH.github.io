# How to use the docs

1. Install [MKDocs - Material](https://squidfunk.github.io/mkdocs-material/getting-started/)

2. Clone the repository with page sources using `git clone repository-name`

3. Edit files in the `docs` directory

4. Check the modifications using `mkdocs serve`

5. Create a build with `mkdocs build` - a directory called `site` will be created

6. Commit using `git add .` and `git commit -m "message"` and upload the changes to GitHub using `git push -u origin main`

7. Upload the build from the `site` directory to branch `gh-pages` using `git subtree push --prefix site origin gh-pages` (the page is served from this branch)

## MKDocs commands

- `mkdocs new [dir-name]` - Create a new project.
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

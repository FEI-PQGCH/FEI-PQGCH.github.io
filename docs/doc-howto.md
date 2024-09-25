# Ako používať dokumentáciu

1. Nainštalovať [MKDocs - Material](https://squidfunk.github.io/mkdocs-material/getting-started/)

2. Stiahnuť repozitár so zdrojom stránok `git clone meno-repozitara`

3. Vykonať úpravy v adresári `docs`

4. Lokálne overiť úpravy príkazom `mkdocs serve`

5. Vytvoriť build príkazom `mkdocs build` - vytvorí sa adresár `site` s vygenerovanými stránkami

6. Commitnúť (`git add .` a `git commit -m "sprava"`) a nahrať zmeny na GitHub pomocou `git push -u origin main`

7. Nahrať build z adresára `site` do branch-e `gh-pages` príkazom `git subtree push --prefix site origin gh-pages` (z tejto branch-e sa stránka zobrazuje)

## MKDocs príkazy

- `mkdocs new [dir-name]` - Create a new project.
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

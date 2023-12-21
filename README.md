# Semantic Methods for Events and Stories (SEMMES)

Workshop at [ESWC 2024](https://2024.eswc-conferences.org/).

## Compile site

```
cd docs
bundle exec jekyll serve --open-url --livereload
```

To re-compute CSS

```
stylus -u nib -u rupture -w --out styles.css -m style/styles.styl
```
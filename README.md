# Антибиотикограмма

Normal build:

```bash
docker run --rm -it -e HUGO_DESTINATION=docs -v $(pwd):/src klakegg/hugo:0.62.0
```

Run server:

```bash
docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:0.62.0 server
```
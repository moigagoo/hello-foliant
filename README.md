# Hello Foliant

## Build the Docs

English version:

```bash
$ docker-compose run --rm -e FOLIANT_FLAGS=en foliant make site
```

Russian version:

```bash
$ docker-compose run --rm -e FOLIANT_FLAGS=ru foliant make site
```

## View the Docs

```bash
$ python -m http.server -d hello-foliant.mkdocs
```

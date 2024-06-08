# okcoder.github.io

## Start development server

```zsh
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```

## Build documentation

```zsh
docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build
```

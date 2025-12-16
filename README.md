# Gupax Website

## About

This repository contains the files for generating statically [gupax.io](https://github.com/gupax-io/site)

## Prerequisites

You need to install [zola](https://www.getzola.org/documentation/getting-started/installation/), a Rust static website generator


## Run

```
git clone https://github.com/gupax-io/site
cd site
git submodule update --init --recursive
zola build
zola serve --open
```

## Contribute

Open an issue to declare a bug or if you want to suggest a feature.

You can check the [TODO](./TODO.md) to see what is needed.

PR are welcomed.

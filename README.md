# quarto-inrae-brand

The goal of this extension is to provide a simple and easy way of producing documents, slides and websites using our institute's brand guidelines, using the new [`brand.yml`](https://posit-dev.github.io/brand-yml/) feature introduced in quarto 1.6

This is a newer and cleaner version of the [`quarto-inrae-extension`](https://github.com/davidcarayon/quarto-inrae-extension) template.

⚠️ This is a Work In Progress ⚠️

## Prerequisites

- Quarto **>= 1.6**

## Installing in a new project

```bash
quarto use template davidcarayon/quarto-inrae-brand
```

## Installing for an existing project

You may also use this extension within an existing project to download only the `_extensions`

```bash
quarto add davidcarayon/quarto-inrae-brand
```

# How to use it

👷 Work In Progress ⚠️

# Live examples of supported formats

- html doc
- html website
- html book
- typst pdf

# Deploying

Here are some templates of Gitlab/Hub Pages configuration files for web deployment

## Github

`pages.yaml`

```yml

```

## Gitlab (Forge INRAE)

`.gitlab-ci.yml` : 

```yml

```

See the wiki for more documentation on deploying websites.

# Future improvements

Once `brand.yml` will support R plots and Shiny Apps through `thematic` and `bslib`, this template may supersed the [`InraeThemes`](https://github.com/davidcarayon/InraeThemes) R Package.




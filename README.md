![forum-header-3](https://user-images.githubusercontent.com/8948187/113044799-5344c780-915b-11eb-80ca-8712a3a09d69.jpg)

# Solana Ecosystem

This repository is the data source for the Solana Ecosystem page, 
located at [solana.com/ecosystem](https://solana.com/ecosystem).

# Contributing Guidelines

A project is composed of two files: a Markdown file with headers, and an 
image. To add a new project to the ecosystem page, create both a new Markdown 
file in the `projects` directory and add a new image in the `img` directory.

__!Important!__:
Should your Project already exist within this repo, refrain from creating a new
Markdown file in the `projects` directory! Rather adapt your old one in a new PR.
Same goes for changed images or Logos for your Project.

### Example File 

```
---
slug: "anchor"
date: "2020-04-03"
title: "Anchor"
logline: "Anchor is a savings protocol that aims to produce a simple and convenient savings product with broad appeal to everyday users."
cta: "https://anchorprotocol.com/"
logo: /img/anchor.svg
category: defi, tools
status: building
---

Anchor is a savings protocol that aims to produce a simple and
convenient savings product with broad appeal to everyday users.
```

Example Markdown headers are above. Below are guidelines for each field:

- `slug`: The page URL that follows after solana.com/ecosystem/
- `date`: The date of project addition
- `title`: The title of the project
- `logline`: The one line summary of the project and its integration to Solana
- `cta`: A URL to direct users to at the bottom of the page
- `logo`: A relative path to the corresponding image
- `category`: A comma separated list of categories describing the project
- `status`: The status of the project: `live`, `building`, or `closed`

### Categories

Available classifications for projects are as follows:

```
amm
app
dapp
defi
dex
exchange
explorer
fund
governance
infra
investmentfund
metaplex
nft
oracle
sdk
spl
stablecoin
tools
wallet
```

Please only use existing ones and *watch out for typos*!  
If you think there is need for another one to be added, ask so in your PR. 

### Image Guidelines

All image files must be 100x100px. Only .svg, .png, and .jpg and .jpeg
files are accepted.

### Prettier

Before submitting a PR, please run Prettier on any files with changes.

## Questions

Have any questions? Email [ryan@solana.com](mailto:ryan@solana.com) or find me on [Discord](https://solana.com/discord)!

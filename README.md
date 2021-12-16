---
# NOTE: This repository is deprecated. To submit your project info, please visit https://solana.com/ecosystem/submit-project.
---

# Solana Ecosystem

This repository is the data source for the Solana Ecosystem page,
located at [solana.com/ecosystem](https://solana.com/ecosystem).

# Contributing Guidelines

A project is composed of two files: a Markdown file with headers, and an
image. To add a new project to the ecosystem page, create both a new Markdown
file in the `projects` directory and add a new image in the `img` directory.

**!Important!**:
Should your Project already exist within this repo, refrain from creating a new
Markdown file in the `projects` directory! Rather adapt your old one in a new PR.
Same goes for changed images or Logos for your Project.

### Example File

```
---
slug: "yourslug"
date: "2020-09-30"
title: "Project Title"
logline: "Write a short description about your project."
cta: "https://yourwebsite.tld/call-to-action"
logo: /img/yourimage.svg
category: amm, app
status: building
website: https://yourwebsite.tld/
twitter: https://twitter.com/yourproject
telegram: https://t.me/yourproject
discord: https://discord.com/invite/12A3bcDE1f
---

This project will look nicely on the ecosystem page and very much advance
the Solana Ecosystem. All while following the community rules, and the ones
stated herein.
```

Example(!) Markdown headers are above. Below are guidelines for each field:

- **(required)** `slug`: The page URL that follows after solana.com/ecosystem/
- **(required)** `date`: The date of project addition
- **(required)** `title`: The title of the project
- **(required)** `logline`: The one line summary of the project and its integration to Solana
- **(required)** `cta`: A URL to direct users to at the bottom of the page
- **(required)** `logo`: A relative path to the corresponding image
- **(enforced)** `category`: A comma separated list of categories describing the project from the ones below!
- **(required)** `status`: The status of the project: `live`, `building`, or `closed`
- **(optional)** `website`: URL to the website (optional)
- **(required)** `twitter`: URL to Twitter page (required)
- **(optional)** `telegram`: URL to Telegram channel (optional)
- **(optional)** `discord`: URL to Discord invite (optional)

### Categories

Available classifications for projects are as follows:

```
amm
app
defi
dex
exchange
explorer
fund
game
governance
infra
investmentfund
metaplex
nft
oracle
rpc
sdk
spl
stablecoin
stake-pool
tools
wallet
```

Please only use existing ones and _watch out for typos_!  
If you think there is need for another one to be added, ask so in your PR.

### Image Guidelines

All image files must be 100x100px / at an aspect ratio of ~1.  
Only .svg, .png, and .jpg and .jpeg files are accepted.
Please refrain from using SVGs with embedded PNG or JPG images!

### Linting

**Everything of the above gets linted against, see the created comments.**

## Questions

Have any questions? Email [ryan@solana.com](mailto:ryan@solana.com) or find me on [Discord](https://solana.com/discord)!

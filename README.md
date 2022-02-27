# kustomize website: the alpha of the alpha

## Overview
This is just an example overview of what the new kustomize website might look like. It is forked from the [docsy exmaple website](https://example.docsy.dev/) and heavy based on that.

I'm not a frontend dev but I was mostly successful at creating what I thought would be a good outline. However, I couldn't get rid of that picture of porridge with blueberries on it on the landing page! So ignore that and imagine it's something more nautical.

## Building

### Docker
Dependencies:
* [docker](https://docs.docker.com/engine/install/)
* [docker-compose](https://docs.docker.com/compose/install/)
```bash
docker-compose build
docker-compomse up -d
```

### hugo
Building using the `hugo` command requires the following dependencies:
* [hugo CLI](https://gohugo.io/getting-started/installing/)
* [Go](https://go.dev/learn/)
* [Node.js](https://nodejs.org/en/)
* npm dependencies
   ```bash
   npm install -D autoprefixer
   npm install -D postcss-cli
   npm install -D postcss
   ```
Start in development mode:
```bash
hugo serve -D
```

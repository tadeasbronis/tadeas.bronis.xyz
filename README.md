# tadeas.bronis.xyz

This repository holds the information, structure and design of [tadeas.bronis.xyz](https://tadeas.bronis.xyz).

## Static website generator

The content is generated with [Hexo](https://hexo.io/), which is as they say: *"A fast, simple & powerful blog framework powered by Node.js"*. It has a lot of plugins and pretty big community.

## Setup local environment

### Prerequisites

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Node.js](https://nodejs.org/en/learn/getting-started/how-to-install-nodejs#how-to-install-nodejs) (recommends 12.0 or higher)
- [hexo](https://hexo.io/docs/#Install-Hexo)

### Running locally

```bash
# Clone repository
git clone git@github.com:tadeasbronis/tadeas.bronis.xyz.git

# Change to directory
cd tadeas.bronis.xyz

# Install packages
npm install

# Pull all git submodules (usually themes)
git submodule update --init --recursive

# Generate static files
hexo generate

# Start the server
hexo server --open
```

### Adding a new post

```bash
hexo new post <title>
```

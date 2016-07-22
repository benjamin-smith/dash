# Dev

## What is this for?

This is a self-contained, mostly zero-configuration environment for developing applications at benjamin-smith. It assumes that you have not installed Docker before.

## The tl;dr Version

    bash <(curl -fsSL https://raw.githubusercontent.com/benjamin-smith/dash/master/bin/bootstrap)
    # Start a new shell and cd to a project that uses [Docker Compose](https://docs.docker.com/compose/)
    dev up

## Step-By-Step Setup

### 1. Run the bootstrap script

This script will install the following:

- Docker
- Docker Compose

and will create:

- An include in your shell profile (bash or zsh)
- A DNS resolver configuration pointing .dev domains to your localhost

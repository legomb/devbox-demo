# Devbox demo

[![Built with Devbox](https://www.jetify.com/img/devbox/shield_moon.svg)](https://www.jetify.com/devbox/docs/contributor-quickstart/)
![build workflow](https://github.com/legomb/devbox-demo/actions/workflows/build.yaml/badge.svg)

Basic [devbox](https://www.jetify.com/devbox) demo.

Demo of a portable, isolated development environment using devbox, which in turn uses nix. Includes Python and uv.

Includes usage example in Github Actions CI.

## Usage

1. Install devbox as per [instructions](https://www.jetify.com/docs/devbox/installing_devbox/?install-method=macos), e.g. for MacOS:

```sh
curl -fsSL https://get.jetify.com/devbox | bash
```

2. Start a new shell that has your packages and tools installed:

```sh
devbox shell
```

## Direnv support

Added as per the [docs](https://www.jetify.com/docs/devbox/quickstart/#use-devbox-with-your-ide):

> Direnv Integration: Devbox can integrate with direnv to automatically activate your shell and packages when you navigate to your project.

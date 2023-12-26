[![Go Reference](https://pkg.go.dev/badge/github.com/disgoorg/disgo.svg)](https://pkg.go.dev/github.com/Amatsagu/Tempest)
[![Go Report](https://goreportcard.com/badge/github.com/disgoorg/disgo)](https://goreportcard.com/report/github.com/Amatsagu/Tempest)
[![Go Version](https://img.shields.io/github/go-mod/go-version/disgoorg/disgo)](https://golang.org/doc/devel/release.html)
[![License](https://img.shields.io/github/license/Amatsagu/tempest)](https://github.com/Amatsagu/Tempest/blob/development/LICENSE)
[![Maintenance Status](https://img.shields.io/maintenance/yes/2024)](https://github.com/Amatsagu/Tempest)
[![CodeQL](https://github.com/Amatsagu/Tempest/actions/workflows/github-code-scanning/codeql/badge.svg?branch=development)](https://github.com/Amatsagu/Tempest/actions/workflows/github-code-scanning/codeql)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)

<img align="left" src="/.github/tempest-logo.png" width=192 alt="Tempest library logo">

# Tempest
Tempest is a [Discord](https://discord.com) API wrapper for Applications, written in [Golang](https://golang.org/). It aims to be fast, use minimal caching and be easier to use than other Discord API wrappers using http.

It was created as a better alternative to [discord-interactions-go](https://github.com/bsdlp/discord-interactions-go) which is "low level" and outdated.

> [!IMPORTANT]
> This branch is highly experimental and is not intended to be used in regular projects.
> It strips Tempest from most of high level abstractions giving more control at cost of reduced options.

### Special features
* [Exposed REST](https://pkg.go.dev/github.com/Amatsagu/Tempest#Client.Rest)
* [Easy dynamic component & modal handling](https://pkg.go.dev/github.com/Amatsagu/Tempest#Client.AwaitComponent)
    - Works with buttons, select menus, text inputs and modals,
    - Supports timeouts,
* Request failure auto recovery (3 attempts)
    - On failed attempts *(probably due to internet connection)*, it'll try again up to 3 times before returning error
* No Discord data caching by default

> [!NOTE]
> This side version of Tempest won't support any new features.

## Troubleshooting
For help feel free to open an issue on github.
You can also inivite to contact me on [discord](https://discord.com/users/390394829789593601).
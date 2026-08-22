# madeintandem/homebrew-tap

Homebrew formulae for tools from [Made In Tandem](https://madeintandem.com).

```sh
brew install madeintandem/tap/tiller
```

Homebrew resolves `madeintandem/tap` to this repository. The formulae under
`Formula/` are written by each tool's release pipeline (GoReleaser, on a tagged
release of the tool's own repository) and are not edited by hand; a change to
a formula is a change to that tool's `.goreleaser.yaml`.

| Formula | Source | What it is |
|---|---|---|
| `tiller` | [madeintandem/tiller](https://github.com/madeintandem/tiller) | An opinionated SDLC workflow tool for humans and AI coding agents working together |

To update a tool you installed from here: `brew upgrade <formula>`.

# InfraZ Homebrew Tap

<img src="https://docs.infraz.io/img/logo/logo_transparent_white.png" width="200">

Official [Homebrew](https://brew.sh) tap for [InfraZ](https://infraz.io) tools.

## Usage

Add the tap:

```sh
brew tap infraz/tap
```

Then install any of the available formulae below.

## Available Packages

### Formulae

| Name | Description |
| --- | --- |
| [`mmdb-cli`](Formula/mmdb-cli.rb) | Command-line toolkit to create, transform, export, and explore MMDB files. |

#### `mmdb-cli`

```sh
brew install infraz/tap/mmdb-cli
```

## Updating

```sh
brew update
brew upgrade mmdb-cli
```

## Uninstalling

```sh
brew uninstall mmdb-cli
brew untap infraz/tap
```

## Notes

Formula definitions in this repository are generated automatically by [GoReleaser](https://goreleaser.com) on each upstream release — do not edit them by hand.

## License

See [LICENSE](LICENSE).

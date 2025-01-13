# <cli_name>

## Documentation

For [installation options see below](#installation).

## Installation

### macOS

#### Homebrew

| Install:                  | Upgrade:                  |
| ------------------------- | ------------------------- |
| `brew install <cli_name>` | `brew upgrade <cli_name>` |

#### MacPorts

| Install:                       | Upgrade:                                               |
| ------------------------------ | ------------------------------------------------------ |
| `sudo port install <cli_name>` | `sudo port selfupdate && sudo port upgrade <cli_name>` |

#### Conda

| Install:                                         | Upgrade:                                        |
| ------------------------------------------------ | ----------------------------------------------- |
| `conda install <cli_name> --channel conda-forge` | `conda update <cli_name> --channel conda-forge` |

#### Spack

| Install:                   | Upgrade:                                         |
| -------------------------- | ------------------------------------------------ |
| `spack install <cli_name>` | `spack uninstall gh && spack install <cli_name>` |

#### Webi

| Install:                                    | Upgrade:                 |
| ------------------------------------------- | ------------------------ |
| `curl -sS https://webi.sh/<cli_name> \| sh` | `webi <cli_name>@stable` |

For more information about the Webi installer see [its homepage](https://webinstall.dev/).

#### Flox

| Install:                  | Upgrade:                |
| ------------------------- | ----------------------- |
| `flox install <cli_name>` | `flox upgrade toplevel` |

For more information about Flox, see [its homepage](https://flox.dev)

### Linux & BSD

`<cli_name>` is available via:

- [our Debian and RPM repositories]

### Windows

#### WinGet

| Install:                               | Upgrade:                               |
| -------------------------------------- | -------------------------------------- |
| `winget install --id <Org>.<cli_name>` | `winget upgrade --id <Org>.<cli_name>` |

#### scoop

| Install:                   | Upgrade:                  |
| -------------------------- | ------------------------- |
| `scoop install <cli_name>` | `scoop update <cli_name>` |

#### Chocolatey

| Install:                   | Upgrade:                   |
| -------------------------- | -------------------------- |
| `choco install <cli_name>` | `choco upgrade <cli_name>` |

#### Signed MSI

MSI installers are available for download on the [releases page][].

## Contributing

To contribute, please follow the guidelines outlined in the [CONTRIBUTING.md](./CONTRIBUTING.md) and the [Code of Conduct](./CODE_OF_CONDUCT.md).

## License

This project is licensed under [Apache 2.0](./LICENSE)

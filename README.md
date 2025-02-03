# golangci-lint-custom-plugins-action

*Unofficial* alternative to [golangci-lint-action](https://github.com/golangci/golangci-lint-action) for use with [custom module plugins](https://golangci-lint.run/plugins/module-plugins/). A request to add mainline support for the module plugin system is tracked as https://github.com/golangci/golangci-lint-action/issues/1076.

> [!WARNING]
> This action does not support the complete set of inputs/features supported by `golangci-lint-action`. If you want to bring it closer to parity, contributions are welcome.

## Usage

For simplest usage with the action defaults:

1. Define your custom `golangci-lint` configuration as `.custom-gcl.yml` in your repository root.
2. *Do not* specify a `name`/`location` in `.custom-gcl.yml`.

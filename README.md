<div align="center">

# asdf-backplane-cli [![Build](https://github.com/mrWinston/asdf-backplane-cli/actions/workflows/build.yml/badge.svg)](https://github.com/mrWinston/asdf-backplane-cli/actions/workflows/build.yml) [![Lint](https://github.com/mrWinston/asdf-backplane-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/mrWinston/asdf-backplane-cli/actions/workflows/lint.yml)


[backplane-cli](https://github.com/openshift/backplane-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add backplane-cli https://github.com/mrWinston/asdf-backplane-cli.git
```

backplane-cli:

```shell
# Show all installable versions
asdf list-all backplane-cli

# Install specific version
asdf install backplane-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global backplane-cli latest

# Now backplane-cli commands are available
ocm-backplane help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrWinston/asdf-backplane-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marius Schulz](https://github.com/mrWinston/)

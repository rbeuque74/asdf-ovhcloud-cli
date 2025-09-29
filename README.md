<div align="center">

# asdf-ovhcloud-cli [![Build](https://github.com/rbeuque74/asdf-ovhcloud-cli/actions/workflows/build.yml/badge.svg)](https://github.com/rbeuque74/asdf-ovhcloud-cli/actions/workflows/build.yml) [![Lint](https://github.com/rbeuque74/asdf-ovhcloud-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/rbeuque74/asdf-ovhcloud-cli/actions/workflows/lint.yml)

[ovhcloud-cli](https://github.com/ovh/ovhcloud-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add ovhcloud-cli https://github.com/rbeuque74/asdf-ovhcloud-cli.git
```

ovhcloud-cli:

```shell
# Show all installable versions
asdf list-all ovhcloud-cli

# Install specific version
asdf install ovhcloud-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf set -u ovhcloud-cli latest

# Now ovhcloud-cli commands are available
ovhcloud --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rbeuque74/asdf-ovhcloud-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Romain Beuque](https://github.com/rbeuque74/)

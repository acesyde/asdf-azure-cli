<div align="center">

# asdf-azure-cli [![Build](https://github.com/acesyde/asdf-azure-cli/actions/workflows/build.yml/badge.svg)](https://github.com/acesyde/asdf-azure-cli/actions/workflows/build.yml) [![Lint](https://github.com/acesyde/asdf-azure-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/acesyde/asdf-azure-cli/actions/workflows/lint.yml)

[azure-cli](https://learn.microsoft.com/en-us/cli/azure/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add azure-cli
# or
asdf plugin add azure-cli https://github.com/acesyde/asdf-azure-cli.git
```

azure-cli:

```shell
# Show all installable versions
asdf list-all azure-cli

# Install specific version
asdf install azure-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global azure-cli latest

# Now azure-cli commands are available
az version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/acesyde/asdf-azure-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Pierre-Emmanuel Mercier](https://github.com/acesyde/)

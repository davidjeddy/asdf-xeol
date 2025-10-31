<div align="center">

# asdf-xeol [![Build](https://github.com/davidjeddy/asdf-xeol/actions/workflows/build.yml/badge.svg)](https://github.com/davidjeddy/asdf-xeol/actions/workflows/build.yml) [![Lint](https://github.com/davidjeddy/asdf-xeol/actions/workflows/lint.yml/badge.svg)](https://github.com/davidjeddy/asdf-xeol/actions/workflows/lint.yml)

[xeol](https://docs.xeol.io/intro) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `git`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add xeol
# or
asdf plugin add xeol https://github.com/davidjeddy/asdf-xeol.git
```

xeol:

```shell
# Show all installable versions
asdf list-all xeol

# Install specific version
asdf install xeol latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xeol latest

# Now xeol commands are available
xeol --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/davidjeddy/asdf-xeol/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David J eddy](https://github.com/davidjeddy/)

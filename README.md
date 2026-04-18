[!WARNING]
**⚠️ This project has been archived and is no longer maintained. ⚠️**

Github has shown it does not respect its users. Other have said it better than I can.

- https://www.theregister.com/2022/06/30/software_freedom_conservancy_quits_github/
- https://www.andrlik.org/dispatches/migrating-from-github-motivation/
- https://techresolve.blog/2025/12/27/looking-to-migrate-company-off-github-whats-the/
- https://lord.io/leaving-github/
- https://dev.to/alanwest/how-to-actually-migrate-from-github-to-codeberg-without-losing-your-mind-33bf>
> Development has moved to Codeberg:
> **➡️ https://codeberg.org/DavidJEddy/asdf-xeol**
>
> Please update your remotes:
> ```bash
> git remote set-url origin https://codeberg.org/DavidJEddy/asdf-xeol
> ```

---
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
# recommended
asdf plugin add xeol https://github.com/davidjeddy/asdf-xeol.git
# using asdf-vm plugins shorthand https://github.com/asdf-vm/asdf-plugins
asdf plugin add xeol
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
<div align="center">

# asdf-safe [![Build](https://github.com/non7top/asdf-safe/actions/workflows/build.yml/badge.svg)](https://github.com/non7top/asdf-safe/actions/workflows/build.yml) [![Lint](https://github.com/non7top/asdf-safe/actions/workflows/lint.yml/badge.svg)](https://github.com/non7top/asdf-safe/actions/workflows/lint.yml)

[safe](https://github.com/Qarik-Group/safe) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add safe
# or
asdf plugin add safe https://github.com/non7top/asdf-safe.git
```

safe:

```shell
# Show all installable versions
asdf list-all safe

# Install specific version
asdf install safe latest

# Set a version globally (on your ~/.tool-versions file)
asdf global safe latest

# Now safe commands are available
safe --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/non7top/asdf-safe/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Vladimir Berezhnoy](https://github.com/non7top/)

<div align="center">

# asdf-hwatch [![Build](https://github.com/chessmango/asdf-hwatch/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-hwatch/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-hwatch/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-hwatch/actions/workflows/lint.yml)


[hwatch](https://github.com/blacknon/hwatch) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add hwatch https://github.com/chessmango/asdf-hwatch.git
```

hwatch:

```shell
# Show all installable versions
asdf list-all hwatch

# Install specific version
asdf install hwatch latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hwatch latest

# Now hwatch commands are available
hwatch -V
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-hwatch/graphs/contributors)!

# License

See [LICENSE](LICENSE)

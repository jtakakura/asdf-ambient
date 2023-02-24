<div align="center">

# asdf-ambient [![Build](https://github.com/jtakakura/asdf-ambient/actions/workflows/build.yml/badge.svg)](https://github.com/jtakakura/asdf-ambient/actions/workflows/build.yml) [![Lint](https://github.com/jtakakura/asdf-ambient/actions/workflows/lint.yml/badge.svg)](https://github.com/jtakakura/asdf-ambient/actions/workflows/lint.yml)


[ambient](https://ambientrun.github.io/Ambient/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `curl`, `unzip`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add ambient
# or
asdf plugin add ambient https://github.com/jtakakura/asdf-ambient.git
```

ambient:

```shell
# Show all installable versions
asdf list-all ambient

# Install specific version
asdf install ambient latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ambient latest

# Now ambient commands are available
ambient --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jtakakura/asdf-ambient/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Junji Takakura](https://github.com/jtakakura/)

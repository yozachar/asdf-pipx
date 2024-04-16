<div align="center">

# asdf-pipx [![Build](https://github.com/yozachar/asdf-pipx/actions/workflows/build.yml/badge.svg)](https://github.com/yozachar/asdf-pipx/actions/workflows/build.yml) [![Lint](https://github.com/yozachar/asdf-pipx/actions/workflows/lint.yml/badge.svg)](https://github.com/yozachar/asdf-pipx/actions/workflows/lint.yml)

[pipx](https://pypa.github.io/pipx/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.
- `python>=3.7`: Python and some dependencies
  - `argcomplete>=1.9.4`
  - `colorama>=0.4.4; sys_platform == 'win32'`
  - `importlib-metadata>=3.3.0; python_version < '3.8'`
  - `packaging>=20.0`
  - `platformdirs>=2.1.0`
  - `userpath>=1.6.0`

# Install

Plugin:

```shell
asdf plugin add pipx
# or
asdf plugin add pipx https://github.com/yozachar/asdf-pipx.git
```

pipx:

```shell
# Show all installable versions
asdf list-all pipx

# Install specific version
asdf install pipx latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pipx latest

# Now pipx commands are available
pipx --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/yozachar/asdf-pipx/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Yozachar](https://github.com/yozachar)

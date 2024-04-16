<div align="center">

# asdf-pipx [![Build](https://github.com/joe733/asdf-pipx/actions/workflows/build.yml/badge.svg)](https://github.com/joe733/asdf-pipx/actions/workflows/build.yml) [![Lint](https://github.com/joe733/asdf-pipx/actions/workflows/lint.yml/badge.svg)](https://github.com/joe733/asdf-pipx/actions/workflows/lint.yml)


[pipx](https://pypa.github.io/pipx/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add pipx
# or
asdf plugin add pipx https://github.com/joe733/asdf-pipx.git
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

[Thanks goes to these contributors](https://github.com/joe733/asdf-pipx/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jovial Joe Jayarson](https://github.com/joe733/)

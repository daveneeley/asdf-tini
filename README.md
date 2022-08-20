<div align="center">

# asdf-tini [![Build](https://github.com/daveneeley/asdf-tini/actions/workflows/build.yml/badge.svg)](https://github.com/daveneeley/asdf-tini/actions/workflows/build.yml) [![Lint](https://github.com/daveneeley/asdf-tini/actions/workflows/lint.yml/badge.svg)](https://github.com/daveneeley/asdf-tini/actions/workflows/lint.yml)


[tini](https://github.com/krallin/tini) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add tini
# or
asdf plugin add tini https://github.com/daveneeley/asdf-tini.git
```

tini:

```shell
# Show all installable versions
asdf list-all tini

# Install specific version
asdf install tini latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tini latest

# Now tini commands are available
tini --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/daveneeley/asdf-tini/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dave Neeley](https://github.com/daveneeley/)

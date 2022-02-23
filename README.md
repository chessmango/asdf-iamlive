<div align="center">

# asdf-iamlive [![Build](https://github.com/chessmango/asdf-iamlive/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-iamlive/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-iamlive/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-iamlive/actions/workflows/lint.yml)


[iamlive](https://github.com/iann0036/iamlive) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add iamlive https://github.com/chessmango/asdf-iamlive.git
```

iamlive:

```shell
# Show all installable versions
asdf list-all iamlive

# Install specific version
asdf install iamlive latest

# Set a version globally (on your ~/.tool-versions file)
asdf global iamlive latest

# Now iamlive commands are available
iamlive -help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-iamlive/graphs/contributors)!

# License

See [LICENSE](LICENSE)

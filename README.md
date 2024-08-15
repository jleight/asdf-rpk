<div align="center">

# asdf-rpk [![Build](https://github.com/jleight/asdf-rpk/actions/workflows/build.yml/badge.svg)](https://github.com/jleight/asdf-rpk/actions/workflows/build.yml) [![Lint](https://github.com/jleight/asdf-rpk/actions/workflows/lint.yml/badge.svg)](https://github.com/jleight/asdf-rpk/actions/workflows/lint.yml)

[rpk](https://github.com/jleight/asdf-rpk) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add rpk
# or
asdf plugin add rpk https://github.com/jleight/asdf-rpk.git
```

rpk:

```shell
# Show all installable versions
asdf list-all rpk

# Install specific version
asdf install rpk latest

# Set a version globally (on your ~/.tool-versions file)
asdf global rpk latest

# Now rpk commands are available
rpk --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jleight/asdf-rpk/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jonathon Leight](https://github.com/jleight/)

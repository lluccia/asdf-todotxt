<div align="center">

# asdf-todotxt [![Build](https://github.com/lluccia/asdf-todotxt/actions/workflows/build.yml/badge.svg)](https://github.com/lluccia/asdf-todotxt/actions/workflows/build.yml) [![Lint](https://github.com/lluccia/asdf-todotxt/actions/workflows/lint.yml/badge.svg)](https://github.com/lluccia/asdf-todotxt/actions/workflows/lint.yml)


[todotxt](https://github.com/todotxt/todo.txt-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add todotxt
# or
asdf plugin add todotxt https://github.com/lluccia/asdf-todotxt.git
```

todotxt:

```shell
# Show all installable versions
asdf list-all todotxt

# Install specific version
asdf install todotxt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global todotxt latest

# Now todo.sh commands are available
todo.sh -h
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/lluccia/asdf-todotxt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Leandro Conca](https://github.com/lluccia/)

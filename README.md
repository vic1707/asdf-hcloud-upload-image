<div align="center">

# asdf-NAME ![Test](https://github.com/vic1707/asdf-NAME/workflows/Test/badge.svg) ![Lint](https://github.com/vic1707/asdf-NAME/workflows/Lint/badge.svg)

</div>

# Contents

-   [Dependencies](#dependencies)
-   [Install](#install)
-   [Usage](#usage)
-   [Contributing](#contributing)
-   [License](#license)

# Dependencies

-   `bash`, `curl` or `wget`, `tar`.

# Install

You can install this plugin to install [NAME](..) repository.
The plugin is dynamic, meaning it can be used for multiple tools without needing to hard-code each one.

```shell
asdf plugin add NAME https://github.com/vic1707/asdf-NAME.git
```

# Usage

```shell
# Show all installable versions
asdf list-all NAME

# Install specific version
asdf install NAME latest

# Set a version globally (on your ~/.tool-versions file)
asdf global NAME latest

# Now your tool's commands are available
NAME --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Possible improvements

-   [ ] -   Try to make the scripts POSIX `sh` compliant because.
-   [x] -   Check all scripts against [asdf banned commands](https://github.com/asdf-vm/asdf/blob/master/test/banned_commands.bats).

# Contributing

Contributions of any kind welcome!

[Thanks goes to these contributors](https://github.com/vic1707/asdf-NAME/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Siegfried Ehret](https://github.com/SiegfriedEhret/)

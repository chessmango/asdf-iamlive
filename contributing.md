# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test iamlive https://github.com/chessmango/asdf-iamlive.git "iamlive -help"
```

Tests are automatically run in GitHub Actions on push and PR.

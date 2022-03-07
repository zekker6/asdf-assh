# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test assh https://github.com/zekker6/asdf-assh.git "assh --help"
```

Tests are automatically run in GitHub Actions on push and PR.

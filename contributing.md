# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test backplane-cli https://github.com/mrWinston/asdf-backplane-cli.git "ocm-backplane help"
```

Tests are automatically run in GitHub Actions on push and PR.

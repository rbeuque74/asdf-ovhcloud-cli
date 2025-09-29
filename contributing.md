# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test ovhcloud-cli https://github.com/rbeuque74/asdf-ovhcloud-cli.git "ovhcloud --help"
```

Tests are automatically run in GitHub Actions on push and PR.

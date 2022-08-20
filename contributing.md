# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test tini https://github.com/daveneeley/asdf-tini.git "tini --help"
```

Tests are automatically run in GitHub Actions on push and PR.

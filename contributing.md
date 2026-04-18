# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test xeol https://github.com/davidjeddy/asdf-xeol.git "xeol --version"
```

Tests are automatically run in GitHub Actions on push and PR.

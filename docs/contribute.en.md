# Contributing
## Library

We use [online-judge-tools/verification-helper](https://github.com/online-judge-tools/verification-helper) for testing.

### Installation

```
pip3 install online-judge-verify-helper
```

### Running Tests

```
oj-verify run
```

Note: It may take some time on the first run.

## Documentation

We use [MkDocs](https://www.mkdocs.org/) for documentation.

### Installation

```
pip3 install mkdocs mkdocs-material mkdocs-static-i18n mike
```

### Deploying Documentation

```
mike deploy [version]
```

Add `--push` to automatically run `git push` as well.

# .github

## Development

To change content of _this_ repository, you might want to install prerequisites
to our pre-commit hooks:

```
sudo dnf install rubygems
```

Checking all files with pre-commit can be done with:

```
pre-commit run --all
```

although just installing [pre-commit](https://pre-commit.com/) is sufficient.

## Badges

| Badge                    | Description          | Service      |
| ------------------------ | -------------------- | ------------ |
| [![Pre-commit][1]][2]    | Static quality gates | pre-commit   |

[1]: https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit
[2]: https://pre-commit.com/

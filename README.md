# pre-commit-mirror-sqlfluff

Mirror of sqlfluff tool for pre-commit

For pre-commit see: https://github.com/pre-commit/pre-commit

For sqlfluff see: https://github.com/alanmcruickshank/sqlfluff

## Usage

**Lint:**

```yaml
- repo: https://github.com/dmateusp/pre-commit-mirror-sqlfluff
  rev: v0.3.5
  hooks:
    - id: sqlfluff
      name: sqlfluff-lint
      args: ['lint']
```

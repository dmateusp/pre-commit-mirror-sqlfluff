# Deprecated!

Now that the `sqlfluff` project hosts pre-commit hooks, this repository is deprecated. Go to https://github.com/sqlfluff/sqlfluff.

The GitHub workflows that refreshed this mirror are turned off, therefore this repository will receive no further updates (post v0.4.0a1).

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

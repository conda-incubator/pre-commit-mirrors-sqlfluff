# sqlfluff mirror

Mirror of sqlfluff for pre-commit with conda as a language.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For sqlfluff: see [here](https://github.com/sqlfluff/sqlfluff)

## Using sqlfluff with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-sqlfluff
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: sqlfluff-conda
```

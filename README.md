sqlfluff(-conda) mirror
===================

Mirror of sqlfluff for pre-commit with conda as a language.

* For pre-commit: see https://github.com/pre-commit/pre-commit
* For sqlfluff: see https://github.com/sqlfluff/sqlfluff

### Using sqlfluff with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-sqlfluff
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: sqlfluff-conda-fix
     - id: sqlfluff-conda-lint
```

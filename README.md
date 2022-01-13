# Problem Example

1. Run `mypy .` - you will only get an error in the `check_me` folder
2. Run `pre-commit run --all-files` - you will get an error in `check_me` and `exclude_me`

Ideally, we should have a way to entirely exclude a folder from being checked.

This is to give a reproduceable example of the issue reported here: https://github.com/pre-commit/mirrors-mypy/issues/1

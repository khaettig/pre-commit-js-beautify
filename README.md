# pre-commit js-beautify
For pre-commit: see https://github.com/pre-commit/pre-commit

For js-beautify: see https://github.com/beautify-web/js-beautify


### Using js-beautify with pre-commit

Add this to your `.pre-commit-config.yaml`:
```yaml
    -   repo: git://github.com/scottybarr/pre-commit-js-beautify
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: js-beautify
```

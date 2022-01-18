# git-hooks

golang hooks for http://pre-commit.com/

Using these hooks
Add this to your .pre-commit-config.yaml

- repo: https://github.com/dnephin/pre-commit-golang
  rev: main
  hooks:
    - id: go-fmt

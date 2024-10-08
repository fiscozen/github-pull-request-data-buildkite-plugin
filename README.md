# Github context variables buildkite plugin
A Buildkite plugin designed to fetch pull request data from GitHub.

## Examples
```yaml
steps:
  - label: ":github: Fetch pull request data from GitHub"
    plugins:
      - ddepaoli3/github-pull-request-data#testing:
          token: $GITHUB_TOKEN
```

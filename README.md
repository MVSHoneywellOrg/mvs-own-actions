# Greeting Action

A simple GitHub Action that greets the provided name.

## Inputs

- `name` (optional): The name to greet. Default is "World".

## Outputs

- `greeting`: The greeting message.

## Example usage

```yaml
jobs:
  greet:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: yourusername/my-greeting-action@v1.0.0
        with:
          name: 'GitHub'
```

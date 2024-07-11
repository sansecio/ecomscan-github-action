# eComscan Github Action

## Usage

```yaml
jobs:
  [...]
  run-ecomscan:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2
    - uses: sansecio/ecomscan-github-action@main
      with:
        key: 'your-custom-key'
        directory: 'your/directory/path'
```

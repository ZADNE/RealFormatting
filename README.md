# RealFormatting

This action checks whether a repo is formatted according to [Real coding style](https://github.com/ZADNE/Real/blob/main/.clang-format).

[RealEngine](https://github.com/ZADNE/RealEngine) and [RealWorld](https://github.com/ZADNE/RealEngine) are formatted using this style.

## Usage

```yaml
- uses: ZADNE/RealFormatting@v0.1
  with:
    # The repository to check formatting of (e.g. ZADNE/RealEngine)
    repository:
    # The branch of the repo to check formatting of (default: main)
    ref:
    # Path within the repo to check formatting of (default: .)
    path:
```
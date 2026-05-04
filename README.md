# release-please-test

Sample repo to test [release-please-action](https://github.com/googleapis/release-please-action).

## Usage

```bash
npm start
```

## How it works

1. Push commits using [Conventional Commits](https://www.conventionalcommits.org/) format to `main`
2. `release-please` automatically opens/updates a Release PR
3. Merging the Release PR creates a GitHub Release and tags

### Commit examples

- `feat: add new feature` → minor version bump
- `fix: resolve bug` → patch version bump
- `feat!: breaking change` or `BREAKING CHANGE:` → major version bump

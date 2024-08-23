# Automated Release

Effortless continuous automated releases using [semantic-release](https://github.com/semantic-release) and []

# Usage

## Package Installation

```bash
pnpm add -D semantic-release @semantic-release/changelog @semantic-release/git @semantic-release/github
```

## Configuration

1. Put `.releaserc.js` in the root of your project
2. Put `.pr-release-template` in the root of your project
3. Put `.github/workflows/release.yml` in the root of your project
3. Put `.github/workflows/create-release-pr.yml` in the root of your project

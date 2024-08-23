# Lint - commitlint

Commit conventions allow your team to add more semantic meaning to your git history. This e.g. includes type, scope or breaking changes.

# Usage

## Package Installation

```bash
pnpm add -D @commitlint/{cli,config-conventional} husky
```

## Configuration

1. Put `commitlint.config.js` in the root of your project
2. git hooks

```bash
pnpm husky init

# Add commit message linting to commit-msg hook
echo "pnpm dlx commitlint --edit \$1" > .husky/commit-msg
```

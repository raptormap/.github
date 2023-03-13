# RAPTOR MAP 🦖

> Welcome to the org !

- [Start Working](#start-working)
- [Contribute](#contribute)
- [Deploy](#deploy)

## Start Working

> [create a fork of our monorepo](https://github.com/raptormap/raptormap)

## Contribute

> [!caution] > **You MUST use [Conventional Commits](tools/Conventional%20Commits.md)**\
> We use an automated versioning process that rely on commit messages for the version bump and changelog.

### Commit message format

```
<type>(<scope>): <message>
```

```
<type>(<scope>): <subject>
<BLANK_LINE>
<body>
<BLANK_LINE>
<footer>
```

### TYPES

`feat` - _A new feature_\
`fix` - _A bug fix_\
`docs` - _Documentation only changes_\
`build` - _Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)_\
`style` - _Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)_\
`refactor` - _A code change that neither fixes a bug nor adds a feature_\
`perf` - _A code change that improves performance_\
`test` - _Adding missing or correcting existing tests_\
`chore` - _Editing comments or README_

## SCOPES

`Auth`\
`Users`\
`Groups`\
`Layers`\
`Features`\
`Types`\
`...`

### BREAKING CHANGES

```
<type>(<scope>)!: <message>
```

```
<type>(<scope>)!: <subject>
<BLANK_LINE>
<body>
<BLANK_LINE>
BREAKING CHANGE: <explanation>
```

### EXAMPLE

```
feat(Layers): add method to update layer
```

```
fix(Layers)!: fix layers imports

add a new thing to that special file
remove that from this

BREAKING CHANGE: an id need to be specified when you call a layer
```


## Deploy

> [use the deploy tools](https://github.com/raptormap/deploy)
# RAPTOR MAP 🦖

> Welcome to the org !

- [🗿 Start Working](#-start-working)
- [🪨 Contribute](#-contribute)
- [🚀 Deploy](#-deploy)

## 🗿 Start Working

### [🐲 MONOREPO](https://github.com/raptormap/raptormap)

steps to start working on raptormap:
- create a fork of the above repository
- clone the newly created fork on your computer
- make some changes and push them **on your fork**
- create a pull request into the raptormap repository from your fork working branch
- wait for the tests to complete and **someone else** to review your code

### Documentation

You will find the documentation in the [docs folder](https://github.com/raptormap/raptormap/tree/main/docs) of the monorepo.\
It is written in markdown but we recommend using [obsidian](https://obsidian.md/) to make things easier.

To use obsidian simply install it and when prompted use `Open folder as vault` and select the `docs` folder from the repository. (Do not open the whole repository in obsidian...)

Alternatively you can use the preview feature of VSCode with `Ctrl`+`Shift`+`V`

## 🪨 Contribute

### ⚠️ You MUST use [Conventional Commits](tools/Conventional%20Commits.md)

> We use an automated versioning process that rely on commit messages for the version bump and changelog.

### Commit Message Format

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

### Types

`feat` - _A new feature_\
`fix` - _A bug fix or code update_\
`docs` - _Documentation only changes_\
`build` - _Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)_\
`style` - _Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)_\
`refactor` - _A code change that neither fixes a bug nor adds a feature_\
`perf` - _A code change that improves performance_\
`test` - _Adding missing or correcting existing tests_\
`chore` - _Editing comments or README_

### Scopes

`auth-ms`\
`chart-ms`\
`gateway`\
`layer-ms`\
`rest-api`\
`solid-app`\
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

### Examples

```
feat(layer-ms): add method to update layer
```

```
fix(layer-ms)!: fix layers imports

add a new thing to that special file
remove that from this

BREAKING CHANGE: an id need to be specified when you call a layer
```


## 🚀 Deploy

### [⚗️ DEPLOY TOOLS](https://github.com/raptormap/deploy)
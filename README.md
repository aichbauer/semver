# SemVer

major.minor.patch

## Changelog

- create a changelog file
  - patch, minor and major version release
    - explain the bug fixes
  - minor and major version release
    - explain new features and how to use them
  - major release
    - explain the breaking changes and how to upgrade

## update the version

update the version within your project.

e.g. package.json, setup.cfg pom.xml,

## create a new commit

```sh
git commit -m "release v1.1.1"
```

## create annotated tag

```sh
git tag -a v1.1.1 -m "release v1.1.1"
```

## release new version

```sh
git push --follow-tags
```

## release on diff. platform

e.g. npm, pip, maven central repository

or to the companies private package manager

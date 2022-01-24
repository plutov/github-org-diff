# github-org-diff

Simple CLI tool to list org repos that have diff between dev and production branches.

***Note: works for orgs that use same branches across all repos, for example `develop` and `main`.***

## Installation

```
go get -u github.com/plutov/github-org-diff
```

## Usage

```
github-org-diff --base=main --head=develop --token=YOUR_OAUTH_TOKEN
```

### CLI args

#### `--base`

Production branch. Default: main

#### `--head`

Dev branch. Default: develop

#### `--token`

Your [personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). Required


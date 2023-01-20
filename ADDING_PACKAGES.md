# Adding a package

1. Make a file at `packages/{name}.json` with this template:
```json
{
    "name": "package name (same as above)",
    "pretty_name": "pretty name (what is used in marketing)",
    "repo": ["RepoOwner", "Repo"],
    "naming_scheme": "A glob that matches against the asset names for each release"
}
```

2. Add the name to [names.json](https://github.com/snowdrop-pm/index/blob/main/names.json)
3. Make a PR!

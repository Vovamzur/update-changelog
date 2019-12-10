Update [Unreleased] in CHANGELOG.md to current package version and add a new one unreleased section at the top

Add script version to package.json:
```
...
"scripts": {
    ...
    "version": "npx update-cl && git add CHANGELOG.md"
}
```
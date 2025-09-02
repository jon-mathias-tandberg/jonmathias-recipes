# jonmathias-recipes

AutoPkg recipes maintained by Jon Mathias Tandberg.

## Usage

Add this repository to AutoPkg:

```
autopkg repo-add https://github.com/jon-mathias-tandberg/jonmathias-recipes.git
```

List recipes:

```
autopkg list-recipes | grep jon-mathias
```

## Structure
- Recipes/<AppName>/<AppName>.download.recipe
- Recipes/<AppName>/<AppName>.intune.recipe (optional)

## License
MIT

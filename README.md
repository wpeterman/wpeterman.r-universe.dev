# wpeterman.r-universe.dev

Registry for the [wpeterman R-universe](https://wpeterman.r-universe.dev).
R-universe reads `packages.json` and rebuilds each listed package from its
GitHub repository whenever that repository changes.

Install the development version of terradish with:

```r
install.packages(
  "terradish",
  repos = c("https://wpeterman.r-universe.dev", "https://cloud.r-project.org")
)
```

# motivation

Take my original mine sweeper experiment, and take the same idea and implement it across multiple clouds, with as many features as possible


constraints

  - AWS secrets as env
  - build time is allowed env for an environment
  - ideally a deploy via a dockerfile
  - minesweeper actual page is a package, ingested by the various apps if needed
  - start with smaller providers
  - review environments will come later
  - every environment has to have an automatic destroy after an hour
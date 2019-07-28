# Suave [![codecov](https://codecov.io/gh/thebiltheory/suave/branch/master/graph/badge.svg)](https://codecov.io/gh/thebiltheory/suave) 
/swɑːv/

A monorepo repo to start your project smoothly.

### What's in this repo

- Code coverage for monorepo


#### Add a local sibling package as dependency

cd into the repository you would like to add as a dependency.
E.g. I would like the `design-system/` as dependency of `web/`.

```bash
cd packages/design-system
```

Then run the following line, which will add a dependency to `@suave/web/package.json`

```bash
lerna add @suave/design-system --scope=@suave/web
```


#### Add a common dependency to all packages


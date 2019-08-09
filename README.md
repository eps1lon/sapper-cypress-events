# sapper-cypress-events

```bash
$ yarn
$ yarn test
# fail
$ yarn dev
$ yarn cy:open
# select tests, pass
# select electron 61 tests fail
```

Manually clicking in electron 61 works so it has something to do with cypress + sapper.

On the `use-export` branch I tried testing with an exported app (using `--legacy`)
but that didn't work either.

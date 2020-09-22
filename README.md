# typescript-eslint-no-semi-repro

Reproduce a case when linter complains about additional semicolor that is added by prettier-standard

1. Install dependencies

```
yarn
```

2. Run the prettier-standard

```
yarn prettier
```

See semicolor added

3. Run the linter

```
yarn lint --fix
```

See semicolor removed


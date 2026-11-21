# knip: SvelteKit 3 `$app/tsconfig` reported as unlisted

```sh
npm install
npm run knip
```

`npm run knip` runs `svelte-kit sync`, which generates `node_modules/$app/tsconfig.json`, then knip:

```
Unlisted dependencies (1)
$app  tsconfig.json
```

knip 6.44.2 reports nothing. 6.45.0 and 6.46.1 report the above.

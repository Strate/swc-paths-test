Steps:

```
git clone git@github.com:Strate/swc-paths-test.git
cd swc-paths-test
npm install
npm test
```

Expected output:

```
SUCCESS
```

Actual output:

```
internal/modules/cjs/loader.js:905
  throw err;
  ^

Error: Cannot find module './core/utilFile'
```


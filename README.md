Trivial example of issue.

```
npm run build
node --enable-source-maps -r tsconfig-paths/register ./dist/a.js
```

When my `tsconfig.json` has `moduleResolution` set to `node` and doesn't have `module` set, there is no issue (original config)

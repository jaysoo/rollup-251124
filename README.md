Running:

```
nx typecheck util2
```

Results in:

```
> tsc --build tsconfig.lib.json

error TS2688: Cannot find type definition file for 'minimatch'.
  The file is in the program because:
    Entry point for implicit type library 'minimatch'


Found 1 error.
```

# missing-tasks-filter-root-repro

```
pnpm i
pnpm run no-error-1 # no filter ✅
pnpm run no-error-2 # no root task ✅
pnpm run no-error-3 # filter + root task with "full name" ✅
pnpm run error # filter + root task with "short name" ❌
```

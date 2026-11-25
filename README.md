# Worst Fix Ever: Funniest Commit Message

Entry for the make.fun competition [#155 "Worst Fix Ever: Funniest Commit Message"](https://make.fun/c/u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722).

## Entry

```
fix: timezone handling for meetings (they now happen yesterday, but on time)
```

## How it works

`main.ts` writes the commit message above to `entry.txt` inside the output
directory given by `MAKEFUN_OUTPUT_DIR` (defaults to `/output`).

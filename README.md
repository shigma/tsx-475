# [privatenumber/tsx#475](https://github.com/privatenumber/tsx/pull/475)

## Reproduction Steps

1. Clone this repository
2. `yarn`
3. `yarn start`

## Real-World Explanation

- `@shigma/a` is a underlying tool library
- `@shigma/b` is a building tool, which depends on `@shigma/a`

Question: can I use `@shigma/b` to build `@shigma/a` with `tsx`?

## day 7

- a gratuitous error on part1 (check that sum of all > test, fails on inputs which contain a 1 and are satisfiable with 1 being multiplied)

possum example with typo

```
equation
equation = record2_sep(f"test", int, ": ", $"numbers", numbers)
numbers = array_sep(int, " ")
```

suboptimal error message

```
[Line 2, 24-30] Error at '"test"': Expected closing ')'
error: UnexpectedInput
```

## day 5

- reported panic in possum: https://github.com/mulias/possum_parser_language/issues/18 (see bug1.possum)

## day 3

- possum `scan` is renamed to `find` but my version still uses `scan`
- part2 more involved and I made a separate 03_2.possum file

this was fun, I enjoyed learning a more advanced pattern for possum

## day 1

- set up repo [x]
- parsing: possum?
  - how to install? [x]
    - donwload binary and possibly notirize on mac
  - run possum with no arguments [x]
    - no need to notariza, just did `chmod +x` and executable is working for me! [x]
  - copied possum to `/usr/local/bin` [x]
  - parse with possum input
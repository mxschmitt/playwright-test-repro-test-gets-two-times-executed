# Playwright Test repro for test file gets executed/loaded two times

## Excpected

```text
Running 1 test using 1 worker

test
  ✓ foo.spec.ts:5:1 › [chromium] should do foo (1ms)


  1 passed (973ms)
```

## Actual

```
test

Running 1 test using 1 worker

test
  ✓ foo.spec.ts:5:1 › [chromium] should do foo (1ms)


  1 passed (973ms)
```

## Note:

- The `test` is logged inside the `foo.spec.ts`.

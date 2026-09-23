# golearn

Hands-on Go fundamentals for a TypeScript developer with a .NET background.

## Purpose

Build up idiomatic Go one small concept at a time, ending with a standalone web service that exercises packages, errors, unit tests, and concurrency. Each step stays small and runnable so the language design is visible without scaffolding a full app early.

## The exercise

We grow a single codebase through a fixed curriculum:

1. Console app: module, `main`, `fmt`, `go run` / `go build`
2. Packages and exports (exported vs unexported names)
3. Types and structs; value vs pointer receivers
4. Interfaces (implicit satisfaction)
5. Errors as values
6. Slices, maps, and `range`
7. Unit tests (`testing`, table-driven tests)
8. Goroutines and channels
9. HTTP server with `net/http`
10. Handlers, routing, and middleware-style wrapping
11. Concurrent request work
12. HTTP tests with `httptestCurrent state: step 1 (console application).

## Run

```bash
go run .
```

Or build a binary:

```bash
go build -o golearn .
./golearn
```

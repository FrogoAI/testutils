# testutils

> A minimalistic, zero-dependency testing helper for Go.

`testutils` is a lightweight alternative to heavy assertion libraries like `testify/assert`. It provides a single "Swiss Army knife" function—`Equal`—that intelligently handles assertions for all kinds of data types, reducing boilerplate without bloating your `go.mod`.

## Key Features

- **The "Switch Knife" Function:** One function (`Equal`) capable of comparing scalars, errors, structs, slices, and maps. You don't need `AssertNil`, `AssertMapEqual`, or `AssertString`.
- **Zero Dependencies:** Keeps your project's dependency graph clean.
- **Reflect-Based:** Automatically handles deep equality checks for complex structures, making it a powerful drop-in for standard Go testing.
- **Readable Output:** formatted error messages when assertions fail, making debugging easier.
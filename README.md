# json-parser
**Warning: this is a learning project. It may be slow, or dysfunctional.
Use [Serde]() instead.**

A JSON parser written in Rust as a learning project.
Inspired by [Douglas Crockford's JSON parser](https://github.com/douglascrockford/JSON-js/blob/master/json_parse.js).

I'm doing this for fun, and to teach myself parser design.

## Things left to implement:
- `null` values
- exponentials
- better errors (no panic)
- (optional) handle floats and integers separately
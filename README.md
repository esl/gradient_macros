# GradientMacros

Compile-time type annotation macros for [Gradient](https://github.com/esl/gradient).

This is a slim repo for inclusion in your project for `MIX_ENV=prod` builds,
so that the entire Gradient repo/package doesn't have to be pulled.

In development (`MIX_ENV=dev` or `MIX_ENV=test`) the real benefit is in
using Gradient (full package) for the reports it provides.


## Installation

```elixir
def deps do
  [
    {:gradient_macros, github: "esl/gradient_macros", runtime: false}
  ]
end
```

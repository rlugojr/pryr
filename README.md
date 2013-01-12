# pryr (rhymes with pry bar)

Tools to pry back the surface of R and dig into the details. 

The easiest way to install `pryr` is with devtools:

```R
library(devtools)
install_github("pryr")
```

## Tools

`pryr` includes tools to better understanding:

* `promises`: `uneval`, `is_promise`, `promise_info`
* scoping and environments: `where`
* closures: `unenclose`
* calls and expressions: `call_tree`

And tools to make it easier to compute on the language:

* `make_function`
* `substitute2`
* `modify_lang`

And to use existing R tools more easily:

* `%<d-%` and `%<a-%` for creating delayed or active bindings
* `rebind` as a more user friendly version of `<<-`
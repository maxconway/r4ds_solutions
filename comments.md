# Comments
- The pie chart question seems like a bad idea. We could not find a clear, elegant answer, and it ends exposing the workings of geom_bar in a way that might be unwise.

- cumulative logical operators probably should not be covered so early. They are a bit difficult to explain, relative to how often they are used. In addition, it seems unwise to introduce row order depended operators before arrange.

- Modular arithmetic should be introduced later than it is. It is an important topic in general programming, but it is not a common function in data science. `ceiling`, `floor`, `trunc`, `round` and `signif` can achieve most or all of the same effects, and can be applied to floating point numbers

- Converting timestamps to times is probably a bit involved for this point in the book, unless you want to give a feel for messy data
Pythonic Objects: implementing productive APIs with the Python Data Model
-------------------------------------------------------------------------

* __Author:__ Luciano Ramalho
* __Video:__ https://www.youtube.com/watch?v=k55d3ZUF3ZQ
* __Slides:__ https://speakerdeck.com/ramalho/pythonic-apis-1


### Highlights

* `__str__` created _to display_ the object to the user, `__repr__` created for _debugging_. With `repr(o)`, if possible, emulate syntax to rebuild object (slides 31-34).
* `reprlib.repr` (slide 34).
* Indexing and slicing with `__getitem__`; `slice` type (slides 35-38).
* `numbers.Integral` represents both _builtin_ and _nympy_ numeric types.
* Python supports fractions: `from fractions import Fraction` (slide 42).
* Python supports `__rmul__` dunder for handling _reversed * operator_ (slides 42-45).
* Implementing `v1 @ v2` multiplication using `__matmul__` and `__rmatmul__` (slides 46-50).
* Basic hashing algorithm: compute the __hash__ of each object attribute or item and aggregate recursively with __xor__ (slides 53-57).

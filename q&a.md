# Q&A

Questions occured during class

### 1. Why `13 and 45` results in `45`?

- According to [Python documentation](https://docs.python.org/3/reference/expressions.html#and), these are intepreted as false in the context of Boolen operations:

    - False
    - None
    - Numeric zero of all types
    - Empty strings and containers (including strings, tuples, lists, dictionaries, sets and frozensets)

- The expression `13 and 45` first evaluates `13`; if `13` is false, its value is returned; but `13` is true because it does not belong to the above, therefore `45` is evaluated, `45` is also true, so the value `45` is returned.

- You can read more about Boolean Operators [here](https://realpython.com/python-boolean/).

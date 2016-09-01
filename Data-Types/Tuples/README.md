# Tuples

A *tuple* is a sequence of Erlang terms with the following properties

* The sequence is of fixed-length
* The sequence is ordered
* The sequence contains a heterogeneous collection of elements (elements could be of same type or wildly different types)

**Literal Syntax**

Tuples are written in curly braces

```erlang
{}
{1, 2, 3, 4, 5}
{one, two, three}
{one, "two", "three"}
{one, {two, "three", {four}}, five}
```

**Convention**

A standard convention in Erlang is to use *tagged tuples*, which uses an *atom* as their first element to indicate what type of data the tuple contains.


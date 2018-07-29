# Elixir Notes

## Basic Types

Integer: 1, 0x1F
Float: 1.0
Boolean: true, false
Atom: :atom
String "test"
List: [1,2,3]
Tuple: {1,2,3}

Method calls can drop the need for ()

* eg: div(10, 2)
* or: div 10, 2

An atom is a constant whose name is its own value. Some other languages call these symbols:

eg: 

iex(1)> :test == :test
    true

iex(2)> :hello == :world
    false

Anonymous functions:

* add = fn a, b -> a + b end
* Starts with an fn and ends with an end
* NB to call add a dot after the var name: iex(4)> add.(1,2)




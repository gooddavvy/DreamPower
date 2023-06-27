# DreamPower
The perfectest coding language. **Still working on it!**

When you're done reading through, check out the examples.

I believe @ThePrimeagen will like this!

# Basics
Be bold! End every stement with an `!`.

```
let const name = "David"!
```

If you're feeling extra-bold, you can do this:

```
let const name = "David"!!!!!
```

In some languages, you use `!` for not. In DreamPower, you use `;`.

```
if ;loved {
  print("I am so sad!")
}
```

# Variables
To declare constants, use `let const`.

```
let const name = "David"!
```

To declare variables, use `let var`.

```
let var name = "David"!
name = "Dave"!
```

# Booleans
Booleans can be `true`, `false`, or `maybe`.

```
let var worldIsLovely = true!
let var christIsOnEarth = false!
let var dreamPowerWillGetPopular = maybe!

if worldIsLovely {
  print("Wow, the world is lovely!")!
}

if ;christIsOnEarth {
  print("Jesus Christ is not on Earth.")!
}

if ?dreamPowerWillGetPopular {
  print("Maybe DreamPower will get popular!")!
}
```

# Types and Type Annotations
DreamPower is a strongly typed programming language.

To declare a type, you use the `let type` keyword.

```
let type Props = map{message: string} | Map<any>!
```

To use a type, you use the `:` token.

```
let var myMap: Props = {message: "Hello world!"}!
```

If you do not provide a value but you provide a type, to a variable, then the variable will have its value as its type's zero/null value.

You can also use builtin types, like `int`, `float`, `bool`, or `string`.

```
let var i: int = 20!
let var f: float = 2.5!
let var b: bool = maybe!
let var s: string = "Hello world!"!
```

# Matrices and Maps
In DreamPower, when it comes to lists, you use matrices instead of arrays. It's fairly simple:

```
let const myMatr = [1, 2, 3]!
print(myMatr)! // Matr[1, 2, 3]
```

And maps, which are similar to JavaScript objects and GoLang maps, in DreamPower, are basically used to store data. You can use a zero value to make a map:

```
let var myMap: map{message: string}!
myMap.message = "Hello world!"!

print(myMap.message)! // Result: Hello world!
print(myMap)! // Result: map{message: "Hello world!"}
```

# Functions

Programmers love shortcuts for their code. These stuff are functions. DreamPower makes them work best. You use `fn`, `fun`, `func`, or `function` to make a function, but `fn` and `fun` are most commonly used.

```
fun addAndPrint(a: int, b: int): int {
  let const sum = a + b!
  print(sum)!
  return sum!
}
```

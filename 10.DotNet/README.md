# .NET

- OOP and Functional programming in .NET
  - How can we achieve immutability in a class?
  By returning a new object of the same class instead of the same object, using Prototype pattern, etc.
  - Give few examples of Higher-order function implementation in .NET?
  Higher-order functions return other functions or take functions as parameters. Most LINQ functions are implemented so - for example, `.Count` function.
  - What is the advantage of using Properties in classes? Can we just use instance variables?
  *Defensive programming*, ensure encapsulation by protecting the instance variable values to be accidently modified to corrupted ones by ensuring check in `set`; `get` can be used to just return the value.
  - How are the *properties* treated by the C# compiler (csc)?
  Properties get converted to `get_propertyName` and `set_PropertyName` methods by the compiler.
  - How to make sure an *invalid* or *illegal* object is not created?
  Error check in `Constructor`, `setter methods`, `methods`

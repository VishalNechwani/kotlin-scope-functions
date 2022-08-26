# kotlin-scope-functions
This is all about the kotlin scope functions

> The Kotlin standard library contains several functions whose sole purpose is to execute a block of code within the context of an object. 
> When you call such a function on an object with a lambda expression provided, it forms a temporary scope.
> In this scope, you can access the object without its name. 
> Such functions are called scope functions. 


There are five of them: let, run, with, apply, and also

Here is a short guide for choosing scope functions depending on the intended purpose:

> Executing a lambda on non-null objects: let
> Introducing an expression as a variable in local scope: let
> Object configuration: apply
> Object configuration and computing the result: run
> Running statements where an expression is required: non-extension run
> Additional effects: also
> Grouping function calls on an object: with

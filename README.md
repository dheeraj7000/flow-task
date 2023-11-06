# flow-task
SomeContract
This contract defines a struct called SomeStruct with 4 variables (a, b, c, d) and 3 functions (publicFunc, contractFunc, privateFunc).
It also defines a resource called SomeResource with 1 variable (e) and 1 function (resourceFunc).
There is a function createSomeResource() that creates an instance of SomeResource.
And a function questsAreFun() that can be called from any area.
Areas
The contract divides code into 4 areas:
AREA 1 - Inside SomeStruct.structFunc() init()
AREA 2 - Inside SomeResource.resourceFunc()
AREA 3 - Inside questsAreFun()
AREA 4 - Not defined
Variable Access
The variables can be read and written to in the following areas:
a: Read in 1,2,3. Written in 1
b: Read in all. Written in 1
c: Read in 1,2. Written in 1
d: Read in 1. Written in 1
Function Calls
The functions can be called from:
publicFunc: All areas
contractFunc: 1,2
privateFunc: 1

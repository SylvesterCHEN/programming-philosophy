# Building Maintainable Software

## Write Short Units of Code

**Limit the length of code units to 15 lines of code**

Do this by not writing units that are longer 15 lines of code in the first place, or by splitting long units into multiple smaller units until each unit has at most 15 lines of code

- When write a new unit
- When extending a unit with new functionality 
- Using refactoring techniques to apply guideline 
	- Extract method
	- Replace method with method object

This improves maintainability because small units are easy to understand, easy to test, and easy to reuse

## Write Simple Units of Code

**Limit the number of branch points per unit to 4**

Do this by splitting complex units into simple ones and avoiding complex units altogether

This improves maintainability because keeping the number of brunch points low makes units easier to modify and test

## Write Code Once

**Do not copy code**

Do this by writing reusable, generic code and/or calling existing methods instead

This improves maintainability because when code is coped, bugs need to be fixed at multiple places, which is inefficient and error-prone

## Keep Unit Interfaces Simple

**Limit the number of parameters per unit to at most 4**

Do this by extracting parameters into objects

This improves maintainability because keeping the number of parameters low makes units easier to understand and reuse

## Separate Concerns in Modules

**Avoid large modules in order to archive loose coupling between them**

Do this by assigning responsibilities to separate modules and hiding implementation details behind interface 

This improves maintainability because changes in a loosely coupled code base are much easier to oversee and execute than changes in a tightly coupled codebase 

## Couple Architecture Components Loosely

**Achieve loose coupling between top-level components**

Do this by minimizing the relative amount of code within modules that is exposed to (i.e., can receive calls from) modules in other components 

This improves maintainability because independent components ease isolated maintenance 

## Keep Architecture Components Balanced

**Balance the number and relative size of top-level components in your code**

Do this by organizing source code in a way that the number of components is close to 9 (i.e., between 6 and 12) and that the components are of approximately equal size

This improves maintainability because balanced components ease locating code and allow for isolated maintenance 

## Keep Your Codebase Small

**Keep your codebase as small as feasible**

Do this by avoiding codebase growth and actively reducing system size

This improves maintainability because having a small product, project, and team is a success factor 

## Automate Tests

**Automatic tests for your codebase**

Do this by writing automated tests using a test framework 

This improves maintainability because automated testing makes development predictable and less risky 

## Write Clean Code

**Write clean code**

Do this by not leaving code smells behind after development work

- Leave no unit-level code smells behind
- Leave no bad comments behind 
- Leave no code in comments behind 
- Leave no dead code behind
- Leave no long identifier names behind
- Leave no magic constants behind
- Leave no badly handled exceptions behind

This improves maintainability because clean code is maintainable code

# Typescript-tutorial
Documenting Typescript
Important aspects in typescript are as follows

1)Type Annotation
2)Interfaces
3)Classes

tsc filename.ts for run the typescript code get converted in to filename.js

=>DataTypes
a)Boolean-true/false value.
b)Number -floating point values.
c)String

  template strings
  
    you can have string plus expressions.
    example
    let fullName: string = `Bob Bobbington`;
    let age: number = 37;
    let sentence: string = `Hello, my name is ${ fullName }.
    I'll be ${ age + 1 } years old next month.`;
 d)Array
 
    Can be represented in two ways
    1)let studentNumber:number[]=[1,2,3];
    2)let studentNumber:Array<number>=[1,2,3];
  e)Tuple
  
    Tuple types allow you to express an array where the type of a fixed number of elements is known, but need not be the same.
  f)enum
  enum Color {Red=1,Orange=2,Black="3"};
  let flowerColor=Color[2];
  
 f)any
 if we dont know the type of the variable.we  can declare it as any and can get opt out of type checking.
 
 g)Void
 h)Null and Undefined
 i)never
 
  The never type represents the type of values that never occur. For instance, never is the return type for a function expression or an arrow function expression that always throws an exception or one that never returns; Variables also acquire the type never when narrowed by any type guards that can never be true.

j)Object
  object is a type that represents the non-primitive type, i.e. any thing that is not number, string, boolean, symbol, null, or undefined.
  
  

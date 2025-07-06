# backend-journey
a backen with full of joy

## Day 1

## Day 2 
### Topics
#### Data Types


Data Type which help us to know what type are data or which format data have returned from the vaiable, 
**Let take a example :**
`
let name = "Masum";
`
In the above line of code, take a variable name __name__ and and stored **text** or **string** value which define the name vaible have a string value.
In the **javascript**, have a fucntion which help to get the type of data `typeof()`, we put the variable inside the funciton get print the type of data.

In the form of, we have two data types in javascript 
##### Primitive 
which holds single value inside the variable 
**like :** `String`, `Boolean`, `Interger`, `Float`, `Null`, `Undefine`.

**`Undefined`** and **`Null`**

undefine data type means define the varible name but never set up any value inside the variable
`let name;`
this `name` variable initialize but inside the varible there is no value assign too.
Simple we can console log it `console.log(name)`
##
null data types define null value inside the variable which reprent null value.

#### Non-Primitive
In the other, we have **Non-Primitive** Data type which holds multi data inside one varible.
**Like :** `Object`, `Array`, `Set`.

**Note :** __`Javascript will return every data types in object in intial stage`__

**`Array`** and **`Object`**

Object store multiple data types with in form of key value pair.
`
let object = {
  'name' : "Masum",'
  'age'  : 22,
  'gender' : "Male",
  'status' : true,
}
`
##
Array holds multiple data types in single form without any pair,

`
let array = ["Masum", 22, {gender: "Male"}, true];
`
##

#### Condition

Conditions in javscript which define break up statement with conditoinal operators in result.

We use `if` and `else` statement in javascript to show up conditional statement with operator check up.

##### Operators

There are 4 types of operator which we have in javascript

##### Assigment Operator
##### Logical 
##### Arithmetic
##### Comparision

###### Arithmetic

In `ifelse` usage of arithmetic and comparision operators

`
function addition(num1, num2){
  return num1 + num2;
}
function subtraction(num1, num2){
  return num1 - num2
}
`
with the help of arithmetic operator `+ (additioni)`, `- (Substraction)`, `* (Multipication)`, `/ (Division)`, `% (Modulus)`, `++ (Increament)`, `-- (Decrement)`, we can conditional rendering.

###### Assigment Operator

with the help of assigment operator, we can assig value `= (assigment)`, += (add assigment), -= (substract assigment) as follows.

`
let number = 7845784578;
//Or
function adding(num1){
  return num1 += 1;
}

`








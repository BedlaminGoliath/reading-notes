# operators

Within JS we have several different "operators". In JS operators are "symbols that we use to either assign, comoare, or perform tasks (think math problems.)

```js
var a = 2

```

here you can see that we used an equal sign, so regularly we would read this as "A 'equals' 2"... however ever in JS we dont use that symbol as an "equal" sign we refer to it as a "assignment" operator, which means we assigned "A" to "2". This is one common use of an operator that, almost everyone venturing into JS has come across atleast once. The "A" and the "2" are called the "operands" while the "=" is called the "operator".

besides this common operator, we have several different other operators (we have 10 different ones). The different types of operators offer different functions. In these notes, i will only focus on 2 common operators.

## Assignment operators

Common operators that people should get used to know are "assignment operators"... Tnese are used to do just as the name suggests they are there to assign values to our variables... specifically our left operand gets assigned to what is on the right of is `` B = 4 `` in this example the letter be got assigned the number four.

The list of types of assigment operators is somewhat extensive which runs from types like "assignment operator", to "addition", "subtraction", "multiplication", "divison", and even runs the gammit to some "obscure" types likeL: "Bitwise..." (which is used to perfomne 'bitwise' operations.)

## Comaprison operators

This series of operators is based around the comparison of both opernands. above we learned about the assignment operator ``=`` however here, we will step up to a ``==`` which is an "equal to" operator which states that the operand on the left is equal to the operand on the right.. here are a few more that are used as well.

* `` === ``  :Equal value and type.

* `` !-- `` :Not equal

* `` !== `` :Not equal value or type.

* `` > `` :Greater than.

* `` < `` :Less than.

* `` >= ``:Greater than or equal to.

* `` <== ``:Less than or equal to.

### Expressions

An expression is a piece of info  that resolves to a single value. This to the example I gave above `` B + C `` this is an expression, this type evaluates and then resolves to a specific value... the actual value itself isnt so important at this moment.

There is another type of expression, a type that we visited in my talk of assignment operators above. `` B = 6 `` this is a type of expression that simply assigns a value to a specific variable... in this case that is "B". Just as there are many different types of operators, we have a few different types of expressions with different functions.

* Arithmetic: evaluates a number 2000291092001

* String: you guess it to a sring ('cat')

* Logical: usually evaluates a true or false statement

* Primary: Basic keywords and basic expressions.

* left-hand-side: where the left side of the operator are the area of assignment.

### Loops

Loops are often used as a quick and easy way to repeat something until a certain condition is met (or condition is evaluated as false).

There are few different necessary expressions needed inorder to ensure a loop functions as it should.. There are several different types of loops however I will talk about two different types.

The ``for`` loop is a 3 part loop (4 for statement)

```js
for([intialExpression]; [conditionExpression]; [incrementExpression])
statement
```
The above example shows the peices needed for a simple ``for`` loop and below we have  "realworld" example. 
```js
for (let jump=0; jump <10; jump ++)
  ```
  
### While loops

Another type of loop is refered to as a "while loop" executes *as long as the conditions evaluates as **true***. This difference is that within a ``for`` loop the amount of loops is already known ``jump <10`` and the loop will run until we get 10 jumps. while a ``while`` loop will run until the specified conditiom is continues to be true.
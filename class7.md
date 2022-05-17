# Control flow

Control flow is the general flow of the script being run. Usually humans read from top to bottom, straight through. However within the realm of coding we have "control flow" this alters the general flow (or progress), Which "conditionals" we are able to make the script get "held up" at a certain *location* for one reason or another... perhaps we cannot submit a form unless the viewer of the page fills out every section of the form, if that is the case then we can set an ``alert`` that is telling the user that "you shall not pass until you fill in this section"... think of this like the main room in Mario 64, you have various doors infront of you, some doors you can open right away, and some doors you cannot open **until** you have a certain amount of stars or keys from previous levels. Maybe, you havent completely finished certain requirements, there for you cannot progress to the later levels (and bonus content) until you have got everything checked off the list. This is a form of "control flow". Instead of being able to just jump from door 1-100 in one run... maybe you got from the start of the level to the end... however you didnt actually complete the necessary challenges, that makes you able to move ahead to complete the story.

## functions

within javascript we have something called a "function". A function isnt *executed* until it is "called upon.

*. A function is defined with the ``function`` keyword that is then followed by the **name** given to the function, that is then followed by a ``()``

*. You can use: letters, dollarsigns, underscores as a function name. (rules like variables).

*. The ``()`` is often used to store parameters of the function.

*. What is actually executed being executed is what is placed within the curly braces.

```js
funcion myFunction(pA, pB) {
    return pA * pB;
}
document.write  = myFunction(4, 5);
```

Here we define the function as "myFunction" we then use  "(pA, pB)" to state the parameters of  the function. Between the curly braces we state what action is being done, so we placed "return" and that is (pA * pB) so its essentially (A x b). After the curly braces we place the "(4, 5)" which is what is actually being used as a "return value"

*. A function can also be considered as a "procedure"

*. when ``return`` is reached the function will reach the end of the function.

### Operators

In Javascript we have "operators" which essentially is just a special symbol that is being used to perform its operation. Think like "+" "=" "*" in math, we have "addition", "equals" (in Js this is actually an assignment operator), and "multiply". However JS has several different ones that you may not be familiar with.

   1.*addition*  ``+``

   2.*subtraction* ``-``

   3.*multiplication ``*``

   4.*exponentation* ``**``

   5.*division* ``/``

   6.*modulus* ``%``

   7.*increment* ``++``

   8.*decrement* ``--``

   9.*assignment* ``=``

this (assignment) operator is worth talking about. This is commonly known as an "equals" sign in standard math, however this is how we *assign* things to variables, the best example i can think of is think of yourself as hungry and say you wanted to write that out. You want to assign yourself to this specific mood or feeling at the moment. you would say  ``Me = hungry``.Here you are not saying ``Me (equals) hungry`` you are assigning yourself to the word (or feeling) of being hungry.

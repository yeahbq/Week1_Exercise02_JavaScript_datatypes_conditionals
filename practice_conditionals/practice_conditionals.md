##Practice Loops, Logic and Conditionals!!!

## COMPARISON OPERATORS
```javascript
3 > 1 && 10 > 1 = true

100 > 200 || 2 > 1 = true

5 === 5 = true

```

[MDN Logical Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators)

So what will these return?

```javascript
"hello" === 'hello' = true
5 === 5 = true
true === false = false
null === null = true
undefined === undefined = true

var a = ["UCLA", "USC"] 
var b = ["UCLA", "USC"]
a === b = true

var x = {name: "Godzilla"}
var y = {name: "Godzilla"}
x === y = true
```

#### True and false, truthy and falsy

In javascript, "true" and "false" are easy to understand. They are exactly what they say they are.

But JavaScript (and most languages) also allow a lot of other things to *evaluate* to true, if we test them. 



```javascript
if(2 > 1){
    console.log("The condition evaluated to true")
}
```"condition evaluated to true"

```javascript
if(true){
    console.log("The condition evaluated to true")
}
```
false no message

Let's try plugging a few others into an if statement:

```javascript
false
1
0 (zero)
-1
"" (empty string)
[] (empty array)
{} (empty object)
null
undefined
NaN (a special Number value meaning Not-a-Number!)
```

## WHILE LOOPS
Create a while loop that will `console.log` every number from 1-9

var i = 1;
console.log(i);
i++;
while (i <= 9); 



As an exercise I want you all to put this into practice

* Create an array of all the members of The Beatles!
* Loop through The Beatles, and console.log each one introducing himself.

## FOR LOOPS
Let's loop through an array of people and `console.log` both the `index` and the `element`.

```js
  var numbers = [1,2,3,4,5,6,7,8,9,10,11,12,13,14];
```

* Create a loop that only prints out multiples of 3.
* Print only even numbers in the array
* Print ONLY values 2 and 3


Why don't we convert our Beatles while loop that we wrote a few minutes ago and convert it to a `for` loop!

## Intermediate task:

4. There is an event with ticket prices that are `$50`, `$65`, `$85` for 
standard, premier, and premier plus (for drinks) seating. Seniors, veterans, 
and students receive a `$10` discount while standard patrons receive no 
discount. Based on hardcoded variables for `ticketType` and `discountType`, 
print out a patrons `ticketPrice`.

----

### TERNARY OPERATOR REFRESHER!

question/conditional ? do this if true : do this if false

```javascript
99 > 1 ? "we return this if the statement is true" : "...and we return this if the statement is false"
```
----

###Your task:

Go back to previous tasks and rewrite them using the ternary

## Close your computers. Let's write on the walls!

* an if/else statement using `&&`
* an if/else statement using `||`
* an if/else statement using `!`
* use the ternary operator









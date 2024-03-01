# What is the difference between Javascript For-In, and For-Of loops ? 

In JavaScript, the `for...of` loop is used to iterate over iterable objects such as arrays, strings, maps, sets, etc. It provides a simpler syntax compared to the traditional for loop when you want to loop through the values of an iterable object without worrying about indexes or accessing elements by index.


<b>Here's the basic syntax of the for...of loop:</b></br>
<code>for (<i>variable</i> of <i>iterable</i>) {
    // code block to be executed</br>
}</code>

<b>- Variable:</b> On each iteration, this variable represents the current value of the iterable being looped over.</br>
<b>- Iterable:</b> This is the object over which the loop iterates. It could be an array, string, map, set, or any other iterable object.</br>

<b>Here's an example of using for...of loop with an array:</b>
<code>
const arr = [1, 2, 3, 4, 5];

for (const element of arr) {
    console.log(element);
}
</code>


In this example, `element` represents the current element of the array `arr` in each iteration of the loop.

You can also use the `for...of` loop with strings:
<code>
const str = 'hello';

for (const char of str) {
    console.log(char);
}
</code>

This will iterate over each character of the string `str`.

The `for...of` loop can also be used with other iterable objects like maps and sets. Here's an example with a Map:
<code>
const map = new Map([
    ['a', 1],
    ['b', 2],
    ['c', 3]
]);

for (const [key, value] of map) {
    console.log(key, value);
}
</code>

In this example, each iteration provides both the key and value of each entry in the map.

Overall, the `for...of` loop simplifies iteration over iterable objects by directly accessing their values without needing to deal with indexes or keys explicitly.


<i>
Aanvullen: </br>
Iterate definition</br>
differences for-in / for-of</br>
</i>

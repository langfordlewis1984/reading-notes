#Problem Domain, Objects, and the DOM

you can change the properties of a CONST's properties

key value pairs - a property name and its value

The const keyword in front of an object implies that there is an object, and you're working with references to alter it. It also (correctly) implies that you should not attempt to reassign references to this object.

const obj = {a: 'foo', b: 'bar'};

const obj2 = {z: 'baz'};

obj = obj2; // const will prevent this operation.
const does not imply that the object properties should not be altered. It does imply that you should not try to change the reference.

https://bioub.github.io/dom-visualizer/

- Begin with a statement addressing why this topic matters as it relates to what you are studying in this module.

DOM manipulation allows HTML to be a lot lighter and allows us to dynamicaqlly add and update information and dataypes

- Answer each and every question or prompt presented in the assignment above.

1. How would you describe an object to a non-technical friend you grew up with?

An object is an entity which is given properties and values. Basically, everything is an object

2. What are some advantages to creating object literals?

dynamicaqlly add and update information and dataypes

3. How do objects differ from arrays?

properties of an object are accessed using their name, elements of an array are accessed using their index.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

Spot.
it's interchangable.

- Make a section in your notes titled ## Things I want to know more about, and anytime a question arises in your mind, or something catches your curiosity, note it under this heading.

- If you utilize any content directly from the reading sources, be sure to identify what you are quoting, and cite the source.

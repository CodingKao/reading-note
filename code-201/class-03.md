# Class 3 Notes

# Introduction to Web Development

#### Link to article: [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
#### Link to article: [The Ordered List Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
#### Link to article: [The Unordered List Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
#### Link to article: [Learn to style HTML using CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
#### Link to article: [The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
#### Link to article: [JavaScript-Dynamic Client](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
#### Link to article: [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
#### Link to article: [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
#### Link to article: [Making Decisions In Your Code - Conditional](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
#### Link to article: [Looping Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

***
>HTML Lists are important because they help organize information on a page in an easy to read format. Control Flow with JS allows developers to create logical pathways and decision making processes in the code, which makes it easier to create complex websites and applications. The CSS Box Model helps developers to create a consistent layout structure and responsive design, which makes it easier to create a website that looks great on any device or browser.


***
## Learn HTML

**When should you use an unordered list in your HTML document?**
>The \<ul> element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Typically, unordered-list items are displayed with a bullet, which can be of several forms, like a dot, a circle, or a square. 

**How do you change the bullet style of unordered list items?**
>You can change the bullet style of unordered list items by using the CSS list-style-type property. The list-style-type property is used to specify the type of list item marker. It can take on a variety of values, including disc, circle, square, decimal, decimal-leading-zero, lower-roman, upper-roman, lower-greek, lower-alpha, lower-latin, upper-alpha, upper-latin, and none.

**When should you use an ordered list vs an unorder list in your HTML document?**
>An ordered list should be used when there is a specific order that needs to be followed, such as a numbered list, or a list of chronological events. An unordered list should be used when there is no important sequence for the items in the list, such as a list of ingredients or features.


**Describe two ways you can change the numbers on list items provided by an ordered list?**
>1. Change the numbers manually: You can change the numbers on list items provided by an ordered list by manually entering the desired number on each list item.
>
>2. Change the start value: You can also change the numbers on list items provided by an ordered list by changing the start value of the list. This will automatically update the number on each item in the list.


***
## Learn CSS
**Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**
> If Margin and padding were two brave knights that defended the castle walls. Margin would be the outermost knight, protecting the castle from any external threats. Padding would be the innermost knight, protecting the castle from any internal danger.

**List and describe the four parts of an HTML elements box as referred to by the box model**
>The CSS box model as a whole applies to block boxes and defines how the different parts of a box — margin, border, padding, and content — work together to create a box that you can see on a page.
>
> - Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
 - Padding box: The padding sits around the content as white space; size it using padding and related properties.
- Border box: The border box wraps the content and any padding; size it using border and related properties.
- Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.


***
## Learn JS

**What data types can you store inside of an Array?**
>You can store any data type, including strings, numbers, objects, booleans, other arrays, and functions.

**Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why**
     const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
>Yes, this is a valid array of arrays.
>
>Items in an array are numbered, starting from zero. This number is called the item's index. So the first item has index 0, the second has index 1, and so on. You can access individual items in the array using bracket notation and supplying the item's index, in the same way that you accessed the letters in a string.

**List five shorthand operators for assignment in javascript and describe what they do.**
>1. += : This operator adds the right operand to the left operand and assigns the result to the left operand.

2. -= : This operator subtracts the right operand from the left operand and assigns the result to the left operand.

3. *= : This operator multiplies the right operand with the left operand and assigns the result to the left operand.

4. /= : This operator divides the left operand by the right operand and assigns the result to the left operand.

5. %= : This operator calculates the remainder of dividing the left operand by the right operand and assigns the result to the left operand.

**Read the code below and evaluate the last expression and explain what the result would be and why.**
>
     let a = 10;
    let b = 'dog';
    let c = false;
    // evaluate this
    (a + c) + b;
>The expression (a + c) + b evaluates to the string '10falsedog'.
>The last expression (a + c) + b evaluates to the string '10falsedog'. This is because (a + c) first evaluates to the number 10 (since false is coerced to the number 0), which is then concatenated with the string 'dog'.

**Describe a real world example of when a conditional statement should be used in a JavaScript program.**
>A real world example of when a conditional statement should be used in a JavaScript program is when a web page needs to respond differently depending on user input. For example, if a user is filling out a registration form, the JavaScript program could use a conditional statement to check if the user has entered all the required fields and display an error message if some of the fields are missing.

**Give an example of when a Loop is useful in JavaScript.**
>Looping is useful in JavaScript when you need to iterate through a collection of data, such as an array or object. For example, you can use a loop to iterate through an array of objects and output the values of a specific property for each object: 
>
    let array = [
    {name: 'John', age: 25},
    {name: 'Jane', age: 23},
    {name: 'Bob', age: 28}
    ];
>
>
    for(let i = 0; i < array.length; i++) {
    console.log(array[i].name); }
>
>// Output: 
>// John
>// Jane
>// Bob
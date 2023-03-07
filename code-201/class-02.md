# Class 2 Notes

# Introduction to Web Development

#### Link to article: [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
#### Link to article: [HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
#### Link to article: [HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)
#### Link to article: [How CSS Is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)
#### Link to article: [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
#### Link to article: [Making Decisions In Your Code - Conditional](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

***
>HTML, CSS, and JavaScript are three of the most important programming languages used to create websites and web applications. HTML is used to define the structure and content of a web page, CSS is used to define the styling and layout of a web page, and JavaScript is used to make a web page interactive. Together, these three technologies are the foundation for creating dynamic, interactive websites and modern web applications.


***
## Introduction to HTML

**Why is it important to use semantic elements in our HTML?**
>Semantic elements are important to use in HTML because they provide structure and meaning to our HTML code. Semantic elements make it easier for search engines and other technologies to interpret the meaning of our content. For example, using semantic elements like \<header>, \<footer>, \<article>, \<section>, and \<nav> allows the search engine to better understand the structure of the page and provide more relevant search results. Additionally, using semantic elements makes the HTML code more organized, readable, and maintainable.

**How many levels of headings are there in HTML?**
>There are six levels of headings in HTML. They are h1, h2, h3, h4, h5, and h6.

**What are some uses for the \<sup> and \<sub> elements?**
>The \<sup> and \<sub> elements can be used to create superscripts and subscripts. They are often used to denote mathematical operations, scientific notation, footnotes, and trademark symbols. They can also be used to denote a person’s name, a date, a trademarked phrase, or any other type of text that needs to be set apart from the rest of the text.


**When using the <abbr> element, what attribute must be added to provide the full expansion of the term?**
>The "title" attribute must be added to provide the full expansion of the term.


***
## CSS
**What are ways we can apply CSS to our HTML?**
>External Stylesheet: An external stylesheet is a separate document linked to an HTML document. It is often a .css file and contains all the styles for a particular website. To link the external stylesheet to the HTML document you would use the \<link> tag in the head section of the document. 
>
>Internal Stylesheet: An internal stylesheet is a set of CSS rules that are written directly inside the head section of an HTML document. It is done using the \<style> tag. This method is usually used when the style rules only apply to the one document and not an entire website.
>
>Inline Styles: Inline styles are rules that are applied directly to an HTML element. This is done using the style attribute. It is usually used when a single element needs to be styled differently than the rest of the document. It is considered a bad practice because it reduces the reusability of the code.

**Why should we avoid using inline styles?**
>First, it is the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website.

**Review the block of code below and answer the following questions:**
>**What is representing the selector?**
>The selector is "h2".
>
>**Which components are the CSS declarations?**
>The CSS declarations are "color: black;" and "padding: 5px;".
>
>**Which components are considered properties?**
>The properties in this code are: color, padding.
>
>    h2 {
>     color: black;
>     padding: 5px;
>    }

***
## Learn JS
**What data type is a sequence of text enclosed in single quote marks?**
>A sequence of text enclosed in single quote marks is a string data type.

**List 4 types of JavaScript operators.**
>1. Arithmetic operators (e.g. +, -, *, /, %, ++, --)
>2. Comparison operators (e.g. >, <, ==, !=, ===, !==, >=, <=)
>3. Logical operators (e.g. &&, ||, !)
>4. Assignment operators (e.g. =, +=, -=, *=, /=)

**Describe a real world Problem you could solve with a Function.**
>Problem: Calculating the total cost of an online shopping order.
>
>Solution: Create a function that takes the prices of each item, the quantity of each item, and the applicable taxes and calculates the total cost.

***
**An if statement checks a __ and if it evaluates to ___, then the code block will execute.**
>condition, true

**What is the use of an else if?**
>An else if statement is used to add another condition to an if statement. It is used when there are multiple possible outcomes and you want to check each one. It allows you to chain multiple if statements together to create more complex logic.

**List 3 different types of comparison operators.**
>=== and !== — test if one value is identical to, or not identical to, another.
>
>< and > — test if one value is less than or greater than another.
>
><= and >= — test if one value is less than or equal to, or greater than or equal to, another.

**What is the difference between the logical operator && and ||?**
>The logical operator && (AND) returns true if both of the expressions on either side of it are true. The logical operator || (OR) returns true if either of the expressions on either side of it are true.
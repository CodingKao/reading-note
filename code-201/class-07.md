# Class 7 Notes

# Object-Oriented Programming, HTML Tables

#### Link to article: [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
#### Link to article: [HTML table basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
#### Link to article: [JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
#### Link to article: [A Beginner's Guide to JavaScript's Prototype](https://ui.dev/beginners-guide-to-javascript-prototype)

> Domain modeling is important because it helps in organizing the data and understanding the relationships between data elements. HTML table basics are important because they provide a structure for displaying data in an organized manner. Constructors are important because they allow developers to create objects from a single class, making the code more efficient and easier to maintain. Object prototypes are important because they provide a template for creating new objects, making the code more efficient and maintainable.


***

## Domain Modeling

**Explain why we need domain modeling.**
> Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.  It is essential in software development as it helps to better understand the problem domain and its requirements. It also provides a better understanding of the data that needs to be stored, processed and retrieved, as well as the relationships between the different entities.


***

## HTML Table Basics

**Why should tables not be used for page layouts?**
> Tables should not be used to create page layouts because they are not designed for that purpose. Tables are intended to display data, not create page layouts. Using tables can create accessibility issues, as well as create issues for mobile devices. Additionally, tables can make it difficult to achieve a responsive design. CSS should be used for page layout instead.
>
>In short, using tables for layout rather than CSS layout techniques is a bad idea. The main reasons are as follows:
>
>Layout tables reduce accessibility for visually impaired users: screen readers, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screen readers' output will be confusing to their users.
>
>Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.
>
>Tables are not automatically responsive: When you use proper layout containers (such as \<header>, \<section>, \<article>, or \<div>), their width defaults to 100% of their parent element. Tables on the other hand are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

**List and describe 3 different semantic HTML elements used in an HTML \<table>..**
> 1. \<th> - This element defines a table header cell and can be used to provide a heading for the table row or column it belongs to.
> 2. \<td> - This element defines a table data cell that contains data related to a particular table header.
> 3. \<tr> - This element defines a table row which is used to group together related table cells.


***

## Introduction Constructors

**What is a constructor and what are some advantages to using it?**
> A constructor is just a function called using the new keyword. When you call a constructor, it will:
>
> - create a new object
> - bind this to the new object, so you can refer to this in your constructor code
> - run the code in the constructor
> - return the new object.
>
> The main advantage of using a constructor is that it allows you to quickly and easily set the initial state of an object without having to manually set each property. It also ensures that all properties are initialized to valid values.

**How does the term this differ when used in an object literal versus when used in a constructor?.**
> When used in an object literal, the term "this" refers to the object itself. When used in a constructor, "this" refers to the instance of the object being created.


***

## Object Prototypes Using A Constructor

**Explain prototypes and inheritance via an analogy from your previous work experience.**
> Prototypes and inheritance are like the chain of command at work. Each employee inherits the expectations from the boss, and then passes along the work and expectations to the next employee in line. This continues until the job is done, and each employee is responsible for passing along the same expectations to the next.

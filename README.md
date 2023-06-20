# Reading notes

## Why do we need domain modelling?

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

## Why should tables not be used for page layouts?

Layout tables reduce accessibility for visually impaired users: screen readers, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screen readers' output will be confusing to their users.

Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.

Tables are not automatically responsive: When you use proper layout containers (such as <header>, <section>, <article>, or <div>), their width defaults to 100% of their parent element. Tables on the other hand are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

## List and describe 3 different semantic HTML elements used in an HTML <table>.

1. <table> is the only semantic element?
2.
3.

## What is a constructor and what are some advantages to using it?

A constructor is a special fuction that creates and initalizes an object instance of a class. They are very useful for creating and initializing multiple objects - saving you time; like creating a blueprint for a house.

## How does the term `this` differ when used in an object literal versus when it's used in a constructor?

Objects created using object literals are singular. This means that when a change is made to the object, it affects that object across the entire script. Whereas, if the object is defined with a function constructor, it allows multiple instances of that object.

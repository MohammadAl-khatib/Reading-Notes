#  Problem Domain, Objects, and the DOM
## The Problem Domain
Understanding problem domain is a key part in desiging a web page, it means to know specifically what the final result will look like, what functions need to be embeded, the inputs and the expected outputs, and any other feature or property in the page.

Unfortunately, it is not always easy to determin the problem domain, sometimes clients and developers have different viewpoints, or the client is not well understanding what he fully needs. This may result in a lot of rework or unfinished business.

Well, what we can do to over come these obstacles, the following guide may give you the answer:

1. Make the problem domain as simple as possible.
2. Communicate to get better understanding.

*read more in* [simpleprogrammer](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)

## Objects
In programming, objects are data models made from variables and functions that resemble real life objects. Object variables and functions are called properties and methods respectively

#### Name Value Pairs
Many features in programming have a system of name value pairs, in HTML we have attributes name and value, in CSS we have property name and value, in JavaScript we have object name (**key**) and value.

#### Creating Objects with Litral Notation

![object declaration image](https://cdn.programiz.com/sites/tutorial2program/files/javascript-object-properties.png)

Note that colon seperates key and value, comma seperates properties and methods inside the object. To acces an object value you can use dot notation, for example the name in our example can be accessed using `person.name`, this property value can be stored in a new variable or used in a function.

## The Document Object Model (DOM)
DOM defines how browsers will create a web page from both HTML and JavaScript files, it reads the HTML as a tree of nodes and asks JavaScript how to interact and update the web page.

The DOM tree consists of:

1. Document node
2. Element node
3. Atribute node
4. Text Node

![DOM tree image](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png)

When browser needs to access the same element more than once, it will cache it i.e. store its location within DOM tree. To select an element; `getElementById()` can be used to target element by its Id, every element has its own unique ID, recently `querySelector()` was added to target elements by CSS selctors.

There are many other selectors, once an element is reached it can be read, updated, used in a function,etc...
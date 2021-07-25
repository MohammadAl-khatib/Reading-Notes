# HTML ,CSS, and JavaScript
## design and build websites
![Logo](https://static.packt-cdn.com/products/9781838648121/graphics/assets/9a5e3a54-0f0e-42a2-ab09-3ab748173cfe.png)
&nbsp;
### How do browsers get information?
Data and information for websites are stored in servers, each server has a unique number called IP number. Each time a browser tries to reach a website, it will connect first to a DNS (Domain Name System) which in turn provides the browser with the required IP address for the website in need.

Think of IP address as a book reference number in a library, the DNS will serve then as librarian that will help you have the book you are searching for. 

When data reaches back to the browser, it will apply certain rules to interpret from HTMl (the language at which websites are designed) to a page readable and organised for the user.
&nbsp;

### Hyber Text Markup Language (HTML)
it is the main language used to structure and build websites, it wraps elements with tags to define the content of the page, will talk briefly about these tags in the following paragraphs.
&nbsp;

#### Doctypes
HTML had a long journey of version evolution, you can dig deeper for the topic on [W3](https://www.w3.org/wiki/Doctypes_and_markup_styles)

#### General Knowledge

Elements of a web page are eighther displayed as ablock or inline block, a block element will take the full width of the page while inline block takes the width of its contents only.

Some elements are block elements by default like paragraphs declared using `<p>` tag some are inline elements like links declared using `<a>` tag.

Grouping of element can also be used using `<div>` and `<span>`, div defines a block element while span defines an inline element.

As you might have noticed, every element is defined by tags, here is a list of tags and their description:

Tag | Function
------------ | -------------
`<!--...-->` | for commenting
`<aside>` | to add extra information
`<iframe>` | add a window for a website inside the page
`<nav>` | for major navigation blocks
`<article>` | for any part that can stand alone like articles and blocks
`<hgroup>` | a set of headings treated as one heading
`<figure>` | for any element that needs caption (reference to a part in the page) like images diagrams graphs
`<figcaption>`| for adding a caption in `<figure>`

### JavaScript
Used to add functionality to the web page, a script is a set of instructions that are used to serve  specific purpose. In order to write a script, define a goal, break to tasks,then write code.

In real world objects are physical, for computer objects are models which are defined according to their properties, events, and methods.

Properties are charectiristics of an object, defined by a name and a value. Events are functions take place when the user interacts with the program. Methods are block of codes that does a specific task.
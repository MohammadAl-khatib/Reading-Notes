# HTML Links, JS Functions, and Intro to CSS Layout
## Links
Links are meant to connect your page to other pages, or to let you navigate to locations inside your page.

The `</a>` is the opening tag inside it you will link a website in `href= ""` between the double cotations, and a description inside `alt= ""`, the link is closed with `</a>` and between the opening and closing tag a text is written or an image is added so the browser will move you to your link when clicking on them. Linking to a part in your page or other pages is possible, just href the id of that part.

![link example image in HTML](https://www.computerhope.com/jargon/h/html-tag.gif)

Links can be used to link external pages, or pages within the same page for which you just have to write its loation inside the repository.

Emails can be linked using `mailto:`

![mailto example image in HTML](https://www.wikihow.com/images/thumb/3/34/Create-an-Email-Link-in-HTML-Step-5.jpg/v4-460px-Create-an-Email-Link-in-HTML-Step-5.jpg.webp)

The link opens by default in the same current window, this can be changed by using `target="_blank"`

## Layout

Firstly, we have to differentiate between block elements and inline elements, block elements take the whole width of a web paage, while inline elements only uses the area of its contents letting elements flow beside each other.

In order to control the position of elements in your website consider the following options:

scheme | description
------------ | -------------
normal flow | block elements will be above each other
relative Positioning | to move top, bot, left, or right but in the same position
absolute positioning | takes the element out of normal flow

![positioning schemes CSS](https://miro.medium.com/max/613/1*pe9E2kzrX48Wwn_0wKklmw.png)
&nbsp;
## Functions, Methods, and Objects

Functions are blocks of code declared to make a specific task. Methods are functions for objects. Objects are models made of data.

To declare a function use the following formula

![declare function in javascript](https://s3.amazonaws.com/codecademy-content/courses/learn-javascript-functions/Diagram/declaration.svg)

To call a function write `functionname();` , functions can take data and return information, for more details visit [Functions,w3schools](https://www.w3schools.com/js/js_functions.asp)
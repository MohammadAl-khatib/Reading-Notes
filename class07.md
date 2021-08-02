# Object-Oriented Programming, HTML Tables
## OOP
Turning real life objects into data models, and problem domain into domain models is called object oriented programming, in the [last reading article](https://mohammadal-khatib.github.io/Reading-Notes/class06) we talked about how to difine objects using litral notation, today we are going to talk about creating objects with constructors.

Many real life objects share common properties, all cars for example have color, specific number of passenger, model, manufacturer, and a plate number. Depending on some of these properties car price can be calculated.

If we are going to turn lets say 10 cars into data models (objects), the result will look sth like this:

`const car1 = {`

`color: red,` 

`numberOfPassengers: 2,`

` model: SLS,`

`manufacturer: Mercedes,`

`palteNumber: 7-82,`

`price: function(){code to calculate price}`

`}`

`const car2 = {`

`color: black,` 

`numberOfPassengers: 4,`

` model: lancer,`

`manufacturer: Mitsubishi,`

`palteNumber: 13-4021,`

`price: function(){code to calculate price}`

`}`

All the way long till car10, as you can see, a lot of line codes will result from such practice, keep in mind that thousands of objects can be found sometimes in one web page.

To eleiminate repitition, constructors can work as a blueprints. Constructors are functions with objects properties as parameters, once defined it can be recalled to create objects more efficiently.

If we want to creat a contructor to our cars example, we will have:

`function car (color,numberOfPassengers,model,manufacturer,palteNumber,price) {`

`this.color = color`

`this.numberOfPassengers=numberOfPassengers`

`this.model=model`

`this.manufacturer=manufacturer`

`this.palteNumber=palteNumber`

`price= function(){code to calculate price}`

Now every car can be created like this:

`car1= new car ('red',2,'SLS','Mecedes','7-82')`

`car2= new car ('black',4,'Lancer','Mitsubishi','13-4021')`

*This is a simple example just for illustration, things may get harder with nested objects, functions, and arrays*

## HTML Tables
![table image](https://cdn.educba.com/academy/wp-content/uploads/2019/10/Create-Tables-in-HTML.png)

a set of tags is used to create tables, you can find each tag's function on [tables, w3schools](https://www.w3schools.com/html/html_tables.asp), most common are `<table>` to creat a table element,`<tr>` for table row, `<td>` for table data, and `<th>` for table header.

Here is an example table in HTML:

`<table>`

`<tr>`

 `<td>&nbsp;</td>`

`<td>Knocky</td>`

`<td>Flor</td>`

 `<td>Ella</td>`

`<td>Juan</td>`

  `</tr>`

  `<tr>`

`<td>Breed</td>`

`<td>Jack Russell</td>`

`<td>Poodle</td>`


`<td>Streetdog</td>`

`<td>Cocker Spaniel</td>`

  `</tr>`

  `<tr>`

 `<td>Age</td>`

`<td>16</td>`

`<td>9</td>`

`<td>10</td>`

`<td>5</td>`

  `</tr>`

  `<tr>`

`<td>Owner</td>`

`<td>Mother-in-law</td>`

`<td>Me</td>`

`<td>Me</td>`

`<td>Sister-in-law</td>`

  `</tr>`

  `<tr>`

   `<td>Eating Habits</td>`

`<td>Eats everyone's leftovers</td>`

 `<td>Nibbles at food</td>`

`<td>Hearty eater</td>`

`<td>Will eat till he explodes</td>`

  `</tr>`

`</table>` 

and the resuling table is:

<table>
  <tr>
    <td>&nbsp;</td>
    <td>Knocky</td>
    <td>Flor</td>
    <td>Ella</td>
    <td>Juan</td>
  </tr>
  <tr>
    <td>Breed</td>
    <td>Jack Russell</td>
    <td>Poodle</td>
    <td>Streetdog</td>
    <td>Cocker Spaniel</td>
  </tr>
  <tr>
    <td>Age</td>
    <td>16</td>
    <td>9</td>
    <td>10</td>
    <td>5</td>
  </tr>
  <tr>
    <td>Owner</td>
    <td>Mother-in-law</td>
    <td>Me</td>
    <td>Me</td>
    <td>Sister-in-law</td>
  </tr>
  <tr>
    <td>Eating Habits</td>
    <td>Eats everyone's leftovers</td>
    <td>Nibbles at food</td>
    <td>Hearty eater</td>
    <td>Will eat till he explodes</td>
  </tr>
</table>



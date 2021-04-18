# **Docs for the HTML `<canvas>` Element & Chart.js**

<img src="https://geoinnova.org/blog-territorio/wp-content/uploads/2020/11/logos.png" width=300px>

## **Canvas**

- `<canvas>` is used to create visual effects in a web page

- the `<canvas>` element requires the closing tag `</canvas>`.

- to display somthing on the `<canvas>` element we use `getContext()`, it's parameter is the type of context to show in the canvas for example `2d`

- you can style a canvas just like any other html element

- the canvas only supports two types of objects 1. rectanles 2. paths , all other shapes must be created by combining one or more paths

- `fillRect(x, y, width, height)` Draws a filled rectangle

- `strokeRect(x, y, width, height)` Draws a rectangular outline

- `clearRect(x, y, width, height)` Clears the specified rectangular area, making it fully transparent

- `(x,y)` are the coordinates for the shape to be drawn

### **Chart.js**

- Chart.js is a `JavaScript` library used to create Charts

- it's built using the `HTML` canvas element

- `<canvas id="buyers" width="600" height="400"></canvas>` - create the canvas element

- `var buyers = document.getElementById('buyers').getContext('2d');` - assign the canvas to a variable and set it's content to 2d drawing

- `new Chart(buyers).Line(buyerData);` - instansiate a new Chart object - .Line is used to draw a line on the canvas

- `buyerData` is an object that contains the information to display on the line chart

- `new Chart(countries).Pie(pieData, pieOptions);` - .Pie is used to draw a pie chart on the canvas

- `pieOptions` is an object that contains options for how to display the data

- `new Chart(income).Bar(barData);` is used to draw a bar chart

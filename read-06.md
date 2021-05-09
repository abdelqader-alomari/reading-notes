### Read: 06 - Programming with JavaScript:
## JavaScript Functions
A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

![JS Functions](https://www.miltonmarketing.com/wp-content/uploads/2018/04/mmjavascriptfunctions234234234functions-min.png)

### Function Invocation
The code inside the function will execute when "something" invokes (calls) the function:

* When an event occurs (when a user clicks a button)
* When it is invoked (called) from JavaScript code
* Automatically (self invoked)

### Function Return
When JavaScript reaches a return statement, the function will stop executing.

![Return](https://www.toolsqa.com/wp-content/gallery/javascript/Functions-in-Javascriptt.png)

### The () Operator Invokes the Function
Using the example above, toCelsius refers to the function object, and toCelsius() refers to the function result.

Accessing a function without () will return the function object instead of the function result.

#### Example:
function toCelsius(fahrenheit) {

  return (5/9) * (fahrenheit-32);

}
document.getElementById("demo").innerHTML = toCelsius;

### Local Variables
Variables declared within a JavaScript function, become LOCAL to the function.

Local variables can only be accessed from within the function.

##### Logic of functions:
![Why functions?](https://personalzone-hulgokm2zfcmm9u.netdna-ssl.com/wp-content/uploads/2017/04/function-basics-diagram.jpg)
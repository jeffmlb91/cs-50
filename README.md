# CS-50

## LEARNING THE FUNDAMENTAL OF JAVASCRIP BY UNDERSTANDING THE KEY CONCEPT 

# GITHUB REPO
- git@github.com:jeffmlb91/cs-50.git

## UNIT 01 - CREATING JAVSCRIPT TAG AND DISPAYING AN ALERT MESSAGE

- DISPLAY HELLO WORLD IN THE CONSOLE
```JS
 // Displaying hello world in the console. 
        console.log("Hello, World!")
```
- ADD AN ALERT AND DISPLAY THE SAME MESSAGE
```JS
   // printing an alert on the browser
     alert("Hello, World!");
```
- CREATE A FUNCTION AND DISPLAY THE ALERT BY PRESSING A BUTTON
```JS
function hello() {
            alert("Hello, World!");
        }
```
```HTML
    <button onClick="hello()">SayHi</button>
```

## UNIT 02 - CHANGING AN ELEMENT CONTENT ON THE PAGE
- CREATE AN HTML H1 WITH SOME CONTENT IN IT
- CREATE A JAVASCRIPT FUNCTION THAT ACCESSES THE TAG AND CHANGE THE CONTENT OF THE ELEMENT

```HTML
    <h1>Good Morning</h1>
    <button onClick="sayHello()">SayHi</button>
```
```JS
    function sayHello() {
            document.querySelector("h1").innerHTML = "Good Afternoon";
        }
```
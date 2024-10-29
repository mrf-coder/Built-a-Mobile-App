# Build-a-Mobile-App counter


  HTML mobile counter app
```js
<html>
    <head>
        <link rel="stylesheet" href="index.css">
    </head>
    <body>
        <h1>People entered:</h1>
        <h2 id="count-el">0</h2>
    </body>
</html>
```
CSS mobile counter app
```js
body {
    background-image: url("[station.jpg](https://picsum.photos/seed/picsum/200/300)");
    background-size: cover;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: bold;
    text-align: center;
}

h1 {
    margin-top: 10px;
    margin-bottom: 10px;
}

h2 {
    font-size: 50px;
    margin-top: 0;
    margin-bottom: 20px;
}

button {
    border: none;
    padding-top: 10px;
    padding-bottom: 10px;
    color: white;
    font-weight: bold;
    width: 200px;
    margin-bottom: 5px;
    border-radius: 5px;
}

#increment-btn {
    background: darkred;
}

#save-btn {
    background: darkgreen;
}

```
#### Change the value of 0 by javaScript DOM method

```js
<html>
    <head>
        <link rel="stylesheet" href="index.css">
    </head>
    <body>
        <h1>People entered:</h1>
        <h2 id="count-el">0</h2>
        <script>
            document.getElementById("count-el").innerText = 5
        </script>
    </body>
</html>
//----------------------------------------------------------------------

//=====seprated JavaScript file index.js link with HTML
<html>
    <head>                                                               JavaScript
        <link rel="stylesheet" href="index.css">               <-----    document.getElementById("count-el").innerText = 5
    </head>
    <body>
        <h1>People entered:</h1>
        <h2 id="count-el">0</h2>
        <script src="index.js"></script>
    </body>
</html>
```

#### Create variable to the console log out

1. Create a variable, myAge, and set its value to your age
2.  2. Log the myAge variable to the console

```js
let count = 0                    //console.log(count)
 console.log(count)              //let count = 0  Error: Cannot access 'myAge' before initialization



let num1 = 35                           // let  count = 5
let  num2= 7                            // count =10
                                        // count=count+20
let result = num1 * num2                // console.log(count)

console.log( result )

 
```

##### Challenge 
Create a variable, bonusPoints. Initialize it as 50. Increase it to 100.
 Decrease it down to 25, and then finally increase it to 70
 Console.log the value after each step

 ```js
  let bonusPoints = 50
console.log(bonusPoints)

bonusPoints = bonusPoints + 50
console.log(bonusPoints)

bonusPoints = bonusPoints - 75
console.log(bonusPoints)

bonusPoints = bonusPoints + 45
console.log(bonusPoints)


```
#### Adding a Button  HTML
```js
 // Create a INCREMENT button with the id="increment-btn"

<html>
    <head>
        <link rel="stylesheet" href="index.css">
    </head>
    <body>
        <h1>People entered:</h1>
        <h2 id="count-el">0</h2>
        <!-- Create a INCREMENT button with the id="increment-btn" -->
        <button id="increment-btn">INCREMENT</button>
        <script src="index.js"></script>
    </body>
</html>
```
#### challege
 intialize the count as 0
 listen for clicks on the increment button
 increment the count variable when the button is clicked
 change the count-el in the HTML to reflect the new count

 ```js
   <html>
    <head>
        <link rel="stylesheet" href="index.css">
    </head>
    <body>
        <h1>People entered:</h1>
        <h2 id="count-el">0</h2>
        <button id="increment-btn" onclick="increment()">INCREMENT</button>
        <script src="index.js"></script>
    </body>
</html>

```
```js
function increment() {
    console.log("The button was clicked")
}
//function 
function countdown() {  
    console.log(5)
    console.log(4)
    console.log(3)
    console.log(2)
    console.log(1)
}
countdown()
countdown()
countdown()
```
#### Create a function 
 Create a function (you decide the name) that logs out the number 42 to the console
 Call/invoke the function
```js
let num = 42;
function number(){
    console.log(num)
}number()
```
let lap1 = 34
let lap2 = 33
let lap3 = 36

###### Create a function that logs out the sum of all the lap times
```js
let lap1 = 34  // Global Scope Variable
let lap2 = 33  // Global Scope Variable
let lap3 = 36  // Global Scope Variable
function totallapps(){
    console.log(lap1+lap2+lap3)
 }totallapps()

//--------make block scope variable -------------------------------
function logLapTime() {
    let totalTime = lap1 + lap2 + lap3 // Block Scop Variable
    console.log(totalTime)
}
console.log(totalTime)//Error Because this variable has block scope
logLapTime()

```
###### Create a function that increments the lapsCompleted variable with one
 Run it three times

```js
   let count = 0;
 function increment(){
    count = count + 1   // or count +=count
}
increment()
increment()
increment()
 console.log(count)   //log out  3
```
intialize the count as 0
listen for clicks on the increment button
increment the count variable when the button is clicked (log it out)
change the count-el in the HTML to reflect the new count
```js
let count = 0

function increment() {
    count = count + 1
    console.log(count)
}
//-------------------------------------
let countEl = document.getElementById("count-el")

console.log(countEl)

let count = 0

function increment() {
    count = count + 1
    countEl.innerText = count
}


```
###### Create a function, save(), which logs out the count when it's called
```js
function save (){                     //HTML
    console.log(count)       // <button id="save-btn" onclick="save()">SAVE</button>
 }  save ()
```
###### Create a variable, message, that stores the string: "You have tree new notifications"

```js
let message = "You have tree new notifications";
console.log(message)

let username = "per"
let message = "You have tree new notifications"

console.log(message + ", " + username + "!")

// Create a variable, messageToUser, that contains the message we have logged
let messageToUser ="that contains the message we have logged"
console.log(messageToUser+ ", " + username + "!")
```
```js
```
```js
```
```js
```
```js
```
```js
```

```js
```
```js
```
```js
```
```js
```
```js
```
```js
```
```js
```
```js
```

```js
```
```js
```
```js
```
```js
```
```js
```
```js
```
```js
```
```js
```

```js
```
```js
```
```js
```
```js
```





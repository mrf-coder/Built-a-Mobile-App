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



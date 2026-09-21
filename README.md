# Ex.No:06 JavaScript Calculator

## AIM

To design and develop a simple calculator using HTML, CSS, and JavaScript to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## ALGORITHM

1. Create an HTML page to design the calculator interface.
2. Create a display field to show the numbers and calculation results.
3. Create buttons for digits from 0 to 9 and arithmetic operators.
4. Use CSS to arrange and style the calculator buttons and display.
5. Write JavaScript functions to handle button clicks.
6. Store the entered numbers and operators in the calculator display.
7. Use JavaScript to evaluate the arithmetic expression.
8. Display the calculated result on the calculator screen.
9. Provide a clear button to reset the calculator.
10. Test the calculator with different arithmetic operations.

## PROGRAM
```
<html>
    <head>
        <title>Calculator</title>
    </head>
    <style>
        .calc{
            width: 300px;
            height: 400px;
            background-color:aqua;
            margin: 50px auto;
            border:1px solid black;
            text-align: center;
            padding-top: 20px;
            border-radius: 10px;
        }
        input[type=text]{
            width: 80%;
            height: 40px;
            margin-bottom: 20px;
            text-align: right;
            font-size: 20px;
        }
        input[type=button]{
            width: 50px;
            height: 50px;
            margin: 5px;
            font-size: 20px;
        }
        input[value=C]{
            background-color:red;
        }
        input[value='=']{
            background-color: black;
            color: white;
        }
        input[value = ]{
            background-color: green;

        }

    </style>
    <body>
        <div class="calc">
            <input type="text" id="cal">

        <h3> Simple Calculator</h3>
        <div id='row'>
            <input type="button" value="1" onclick="cal.value+=('1')">
            <input type="button" value="2" onclick="cal.value+=('2')">  
            <input type="button" value="3" onclick="cal.value+=('3')">
            <input type="button" value="+" onclick="cal.value+=('+')">
        </div>
        <div id='row'>
            <input type="button" value="4" onclick="cal.value+=('4')">
            <input type="button" value="5" onclick="cal.value+=('5')">
            <input type="button" value="6" onclick="cal.value+=('6')">
            <input type="button" value="-" onclick="cal.value+=('-')">
        </div>
        <div id='row'>
            <input type="button" value="7" onclick="cal.value+=('7')">
            <input type="button" value="8" onclick="cal.value+=('8')">
            <input type="button" value="9" onclick="cal.value+=('9')">
            <input type="button" value="*" onclick="cal.value+=('*')">
        </div>
        <div id='row'>
            <input type="button" value="0" onclick="cal.value+=('0')">
            <input type="button" value="=" onclick="cal.value=eval(cal.value)">
            <input type="button" value="C" onclick="cal.value=('')">
            <input type="button" value="/" onclick="cal.value+=('/')">
        </div>
    </body>
</html>
```


## OUTPUT

![alt text](<Screenshot 2026-09-02 083415.png>)

## RESULT

Thus, a JavaScript-based calculator was successfully designed and developed to perform basic arithmetic operations using HTML, CSS, and JavaScript.

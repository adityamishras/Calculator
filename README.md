# Calculator
Hello Everyone, this a simple calculator using html, Css, and Javascript . Coding is very simple and easy to understand.

```html & JS
<body>
    <div class="container">
        <div class="calculator">
            <form action="">
                <div class="display">
                    <input type="text" name="display">
                </div>
                <div>
                    <input type="button" value="AC" onclick="display.value='' ">
                    <input type="button" value="DE" onclick="display.value= display.value.toString().slice(0,-1)">
                    <input type="button" value="."  onclick="display.value +='.'">
                    <input type="button" value="/"  onclick="display.value +='/'">
                </div>
                <div>
                    <input type="button" value="7" onclick="display.value +='7'">
                    <input type="button" value="8" onclick="display.value +='8'">
                    <input type="button" value="9" onclick="display.value +='9'">
                    <input type="button" value="*" onclick="display.value +='*'">
                </div>
                <div>
                    <input type="button" value="4" onclick="display.value +='4'">
                    <input type="button" value="5" onclick="display.value +='5'">
                    <input type="button" value="6" onclick="display.value +='6'">
                    <input type="button" value="-" onclick="display.value +='-'">
                </div>
                <div>
                    <input type="button" value="1" onclick="display.value +='1'">
                    <input type="button" value="2" onclick="display.value +='2'">
                    <input type="button" value="3" onclick="display.value +='3'">
                    <input type="button" value="+" onclick="display.value +='+'">
                </div>
                <div>
                    <input type="button" value="00" onclick="display.value +='00'">
                    <input type="button" value="0" onclick="display.value +='0'">
                    <input type="button" value="=" onclick="display.value=eval(display.value)" id="equalbtn">
                </div>
            </form>
        </div>
    </div>
</body>

```

#CSS 
```css


```

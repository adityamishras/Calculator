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
* {
  margin: 0;
  padding: 0;
}
.container {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.calculator {
  background-color: rgb(63, 63, 63);
  padding: 20px;
}
.display {
  display: flex;
  justify-content: flex-end;
  margin: 20px 0;
}

.calculator form input {
  border: 0;
  outline: 0;
  width: 60px;
  height: 60px;
  border-radius: 10px;
  margin: 10px;
  background-color: transparent;
  font-size: 20px;
  cursor: pointer;
  box-shadow: -8px -8px 15px rgba(255, 255, 255, 0.1),
    5px 5px 15px rgba(0, 0, 0, 0.1);
  color: white;
}
.calculator form #equalbtn {
  width: 142px;
}
form .display input {
  flex: 1;
  text-align: right;
  padding-right: 10px;
  box-shadow: none;
  font-size: 50px;
}

@media (max-width:375px) {

  .calculator form input {
    width: 40px;
    height: 40px;
    margin: 6px;
    font-size: 15px;
  }
  .calculator form #equalbtn {
    width: 100px;
  }
  form .display input {
    box-shadow: none;
    font-size: 40px;
  }

}

```
## Screenshots

![App Screenshot](https://github.com/adityamishras/Calculator/assets/136791974/cf4de489-0705-4a22-8d42-48efb5ffca56)

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://adityamishras.github.io/page/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adityamishras)
[![instagram](https://img.shields.io/badge/instagram-1DA1F2?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/adityamishras)


## Video
<a href="https://github.com/adityamishras/Calculator/assets/136791974/54e9506e-7800-450b-9804-58ac6c644cc7" target="_blank">
    <img src="https://github.com/adityamishras/Calculator/assets/136791974/4f6f9ccf-6f3a-475c-9c4b-7bd964a4cfda" width="600" />
</a>


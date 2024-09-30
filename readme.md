                        JavaScript
                       Assignment 3

1.The value of numb1 =?
Let numb1 = 12
Numb1 /= 3
```js
            let a=12
            let b=2
            a/=b
            console.log(a=a/b);
    output:3
```
2.What does ‘a’ equal?
Let a = 17 % 4
```js
        let a=17
        let b=4
        console.log(a=a%b);
    output:a=1
```
3.What does x++ equals?
```js

        let x=3
        console.log(++x);
    output:4

        
        let x=3
        x++
        console.log(x);
    output:4
```
4.Create a Fahrenheit to Celsius converter
C = ((F -32) * 5) / 9
```js
        let celcius= prompt("Enter The Temp In Celcius")
        f=(celcius*9/5)+32
        let message="Your Current Temp Is"
        alert(`${message} ${f}`)
```

5.Create a discount percentage calculator
discountPercentage = ((MRP – sellingPrice) * 100) / MRP
```js
let mrp=prompt("Enter The MRP:")
let sellingPrice=prompt("Enter The Selling Price:")
let discountPercentage=((mrp-sellingPrice)*100)/mrp
alert(`${discountPercentage}`)
```

6.Create a BMI Calculator 
BMI = Weight(kg) / (height(m) * height(m))
```js
let height=prompt("Enter Your Height(m):")
let weight=prompt("Enter Your weight(kg):")
let BMI=weight/(height*height)
alert(`your BMI is ${Math.round(BMI)}`)
```
Значение переменной variable будет равно '115'. В переменной будет храниться строка, а не число.

```js
let variable = 1 + '15'
console.log(variable) // '115'
```

Оператор _+_ в JavaScript используется для сложения чисел или конкатенации строк. В результате применения этого оператора к двум значениям получится строка или число. Если один из операндов будет строковым типом, то оба операнда сначала будут приведены к строке, а результатом станет их конкатенация.
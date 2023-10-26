---
title: ".concat()"
description: "Способ быстро и просто склеить несколько массивов или строк."
authors:
  - doka-dog
related:
  - js/arrays
  - js/string
  - js/array-flat
tags:
  - doka
  - placeholder
---

## Кратко

Метод `.concat()` склеивает вместе массив или строку с переданными внутрь него аргументы. Может применяться для [массивов](/js/arrays/) и [строк](/js/string/).

## Пример

Склеим два массива:

```js
let animals = ['Ореховая соня', 'Голый землекоп', 'Полосатый тенрек']
let flowers = ['Камелия китайская', 'Кофейное дерево']

let mix = animals.concat(flowers)
console.log(mix) // ['Ореховая соня', 'Голый землекоп', 'Полосатый тенрек', 'Камелия китайская', 'Кофейное дерево']
```

Склеим и дополним две строки:

```js
let animal = 'Ореховая соня'
let flower = 'Какао настоящее'

let mix = animal.concat(' спит в ', flower)
console.log(mix) // Ореховая соня спит в Какао настоящее
```

## Как пишется

Метод вызывается для массива или строки. Внутри круглых скобок записывается любое количество аргументов. Каждый аргумент будет «пристыкован» в конец к исходному массиву или строке. Можно передавать как переменные, так и сразу значения.

Не изменяет исходные данные, возвращает новое значение.
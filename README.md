# javascript-tasks
Задачи для изучающих JavaScript

## 1. Рекурсия

**Задача 1.1.** 
Сложность: :star:

Напишите функцию ```sumTo(n)```, которая для данного ```n``` вычисляет сумму чисел от 1 до ```n```, например:

```
sumTo(1) = 1
sumTo(2) = 2 + 1 = 3
sumTo(3) = 3 + 2 + 1 = 6
sumTo(4) = 4 + 3 + 2 + 1 = 10
...
sumTo(100) = 100 + 99 + ... + 2 + 1 = 5050
```

> Источник: https://learn.javascript.ru/recursion

---

**Задача 1.2.**
Сложность: :star:

Напишите функцию ```factorial(n)```, которая возвращает факториал числа ```n!```, используя рекурсивный вызов.

> Источник: https://learn.javascript.ru/recursion

---

## 2. Функции-конструкторы

**Задача 2.1.** 
Сложность: :star::star:

Реализуйте на ES5:

```
var c = new Counter();
var a = c.next(); // 1
var b = c.next(); // 2
```

---

## 3. Функции и контекст вызова

**Задача 3.1.** 
Сложность: :star::star:

Реализуйте функцию ```add``` таким образом, чтобы примеры ниже работали:

```
add(2, 5); // 7
add(2)(5); // 7
```

> Источник: https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/src/questions/coding-questions.md

---

**Задача 3.2.** 
Сложность: :star::star:

Исправьте код таким образом, чтобы вызов функции на последней строке выводил в консоль имя Sam:

```
var person = {
    name: "Sam",
    hello: function() {
        console.log(this.name);
    }
};
var hello = person.hello;
hello(); 
```

> Источник: https://github.com/vvscode/js--interview-questions/blob/master/topics/inheritance-vs-context.md

---

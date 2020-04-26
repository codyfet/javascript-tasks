# javascript-tasks
Задачи для изучающих JavaScript

:star: - элементарные

:star::star:- базовые

:star::star::star: - продвинутые

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

**Задача 3.3.** 
Сложность: :star::star:

Реализуйте функцию union(), которая объединит уникальные элементы всех массивов, переданных ей.
Пример использования: ```union([1, 2, 2, 3], [101, 2, 1, 10], [2, 1])```
Результат выполнения: ```[1, 2, 3, 101, 10]```.

> Источник: https://veronikanovikova.github.io/js-tasks/

---

## 4. Замыкания
**Задача 4.1.** 
Сложность: :star::star:

Как исправить код ниже, чтобы он выел в консоль 5 разных значений (от 0 до 4):

```
for (var i = 0; i < 5; i++) {
    setTimeout(function() {
        console.log(i);
    }, 1000);
}
```

> Источник: https://github.com/vvscode/js--interview-questions/blob/master/topics/closures.md

---

## 5. Прототипы, методы
**Задача 5.1.** 
Сложность: :star::star:

Реазлизуйте метод класса Array forEach2, который будет работать точно также, как и существующий метода forEach. 

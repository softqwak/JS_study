
# План изучения JavaScript

Этот план направлен на углубленное изучение JavaScript, основываясь на текущих знаниях в программировании. Он охватывает основные концепции и включает полезные ресурсы для самостоятельного изучения.

---

## 1. Основы JavaScript и особенности языка

### Темы:
- **Типы данных и преобразования:** Особенности динамической типизации, явные и неявные преобразования, сравнение `==` и `===`.
- **Основные структуры данных:** Объекты, массивы и работа с ними (методы `.map()`, `.filter()`, `.reduce()`, отличие `forEach` от `for...of`).

### Полезные ссылки:
- [MDN Web Docs: Типы данных и структуры](https://developer.mozilla.org/ru/docs/Web/JavaScript/Data_structures)
- [MDN Web Docs: Преобразования типов](https://developer.mozilla.org/ru/docs/Web/JavaScript/Guide/Expressions_and_Operators#type_conversions)
- [JavaScript.info: Типы данных](https://learn.javascript.ru/types)

**Упражнение:** Напиши функцию, которая принимает массив и возвращает новый массив с уникальными значениями, например, `[1, 2, 2, 3] -> [1, 2, 3]`.

---

## 2. Функции, стрелочные функции и замыкания

### Темы:
- **Функции и их виды:** Стрелочные функции (`=>`), различия между `function` и стрелочными функциями, поведение `this`.
- **Замыкания:** Как функции "запоминают" область видимости, где они были объявлены.

### Полезные ссылки:
- [JavaScript.info: Замыкания](https://learn.javascript.ru/closure)
- [MDN Web Docs: Стрелочные функции](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
- [Medium: Understanding Closures in JavaScript](https://medium.com/javascript-in-plain-english/javascript-closures-explained-in-plain-english-19650f4de3e2)

**Упражнение:** Создай функцию `counter`, которая использует замыкание для сохранения счётчика и возвращает объект с методами `increment` и `decrement`.

---

## 3. Объектно-ориентированное программирование (ООП) в JavaScript

### Темы:
- **Прототипное наследование:** Как работает наследование через прототипы.
- **Классы и методы:** Использование классов и методов в JavaScript.

### Полезные ссылки:
- [MDN Web Docs: Прототипы и наследование](https://developer.mozilla.org/ru/docs/Learn/JavaScript/Objects/Inheritance)
- [JavaScript.info: Классы](https://learn.javascript.ru/classes)
- [FreeCodeCamp: Understanding Prototypes in JavaScript](https://www.freecodecamp.org/news/understanding-javascript-prototypes-24cd91513440/)

**Упражнение:** Создай класс `Car` с методами `start` и `stop`, и класс `ElectricCar`, у которого есть метод `charge`.

---

## 4. Работа с DOM и событиями

### Темы:
- **Изменение DOM:** Взаимодействие с HTML-документом через JavaScript (`document.querySelector`, `addEventListener`).
- **События:** Обработка событий, делегирование событий.

### Полезные ссылки:
- [JavaScript.info: DOM-дерево](https://learn.javascript.ru/dom-nodes)
- [MDN Web Docs: Работа с DOM](https://developer.mozilla.org/ru/docs/Web/API/Document_Object_Model/Introduction)
- [W3Schools: JavaScript Events](https://www.w3schools.com/js/js_events.asp)

**Упражнение:** Сделай простую форму с полем ввода и кнопкой. При нажатии на кнопку текст отображается на странице.

---

## 5. Асинхронное программирование

### Темы:
- **Основы асинхронности:** `setTimeout`, `setInterval`, промисы (`Promise`), `async` и `await`.
- **Работа с API:** Отправка запросов с использованием `fetch` и обработка данных.

### Полезные ссылки:
- [JavaScript.info: Асинхронность, колбэки, промисы](https://learn.javascript.ru/async)
- [MDN Web Docs: Промисы](https://developer.mozilla.org/ru/docs/Web/JavaScript/Guide/Using_promises)
- [MDN Web Docs: Fetch API](https://developer.mozilla.org/ru/docs/Web/API/Fetch_API/Using_Fetch)

**Упражнение:** Создай функцию, которая запрашивает данные с публичного API (например, [JSONPlaceholder](https://jsonplaceholder.typicode.com/)) и отображает информацию на странице.

---

## 6. Практика и проекты

### Идея для проекта:
Создай приложение для заметок или To-Do list, позволяющее добавлять и удалять задачи. Это поможет закрепить все изученные темы.

---

## Заключение
Этот план позволит последовательно освоить основные концепции JavaScript и подготовиться к созданию более сложных приложений.

<div align="center">
# Министерство образования и исследований
## Молдавский Государственный Университет
### Факультет Математики и Информатики 
#### Департамент Информатики
<br>
Отчет
по дисциплине «Javascript»
Лабораторная работа № 1.
Введение в JavaScript.
<br> <br>
Выполнила:
Чебанова София, гр. IA2503
Проверил:
N.Calin, asistent universitar
<br><br>
Кишинев, 2025

</div>




# Лабораторная работа №1
# Введение в JavaScript

## Цель работы:
Познакомиться с основами языка JavaScript, научиться выполнять код в браузере и в локальной среде, а также изучить базовые конструкции языка.

## Ход выполнения работы
### Задание 1. Выполнение кода в браузере

В ходе работы была подготовлена среда разработки: установлен текстовый редактор VS Code, Node.js, а также использованы инструменты разработчика браузера (DevTools).

В консоли браузера(рис.1) был выполнен следующий код:

```js
console.log("Hello, world!");
2 + 3
```
<img width="427" height="252" alt="image" src="https://github.com/user-attachments/assets/69f35a5e-7403-455e-9d29-5b84e1498160" />

Рис.1. Код выполненый в консоли браузера.

В результате в консоль было выведено сообщение и вычислено арифметическое выражение.

### Создание HTML-страницы с JavaScript
Был создан файл index.html, в который был добавлен встроенный JavaScript-код:
```html
<script>
  alert("Привет, мир!");
  console.log("Hello, console!");
</script>
```
При открытии страницы в браузере появилось всплывающее окно(рис.2), а сообщение было выведено в консоль.
<img width="599" height="224" alt="image" src="https://github.com/user-attachments/assets/708b76f4-e372-4bf2-a6b8-d11234cbdfb7" />

рис.2. Всплывающее окно.  

<img width="266" height="153" alt="image" src="https://github.com/user-attachments/assets/d2bd2afe-8070-4983-99f2-960829e47275" />
                                               
рис.3. Сообщение в консоли.

### Подключение внешнего JavaScript-файла

Был создан внешний файл script.js, который был подключён к HTML-документу:
```html
<!DOCTYPE html>
<html lang="en">
 <head>
     <script src="script.js"></script>
   <title>Привет, мир!</title>
 </head>
 <body>
 </body>
</html>
```

<img width="906" height="141" alt="image" src="https://github.com/user-attachments/assets/b5e738b9-0795-4225-9c10-2fa04dde8ce0" />
рис.4. Javascript-код в подключенном файле.


```js
alert("Этот код выполнен из внешнего файла!");
console.log("Сообщение в консоли");
```
<img width="1379" height="302" alt="image" src="https://github.com/user-attachments/assets/037e33e4-ce1c-4f79-aa69-d5b3c9a99143" />
<img width="444" height="143" alt="image" src="https://github.com/user-attachments/assets/856ccb14-4b60-48bc-8dfc-af8af8ad11f6" />

рис.5, 6. Демонстрация работы кода.

## Задание 2. Работа с типами данных

В файле script.js были объявлены переменные различных типов данных:
```js
let name = "Sofia";
let birthYear = 2007;
let isStudent = true;
console.log(name);
console.log(birthYear);
console.log(isStudent);
```
<img width="366" height="213" alt="image" src="https://github.com/user-attachments/assets/f81d6d01-9871-40e8-b4dd-b1d96f28cae5" />

Рис.7. Вывод переменх в консоль.

Также были реализованы условные операторы и цикл for:
```js
let score = prompt("Введите ваш балл:");
if (score >= 90) {
 console.log("Отлично!");
} else if (score >= 70) {
 console.log("Хорошо");
} else {
 console.log("Можно лучше!");
}

for (let i = 1; i <= 5; i++) {
 console.log(`Итерация: ${i}`);
}
```
<img width="894" height="309" alt="image" src="https://github.com/user-attachments/assets/da613d5f-f5ba-46dc-9d60-e55809aaaa62" />

<img width="1732" height="282" alt="image" src="https://github.com/user-attachments/assets/2f57b857-1357-40df-a8d6-584dc8998229" />

Рис.8, 9. Выполнение кода в браузере.

## Результаты выполнения

В ходе выполнения лабораторной работы был изучен процесс запуска JavaScript-кода в браузере, работа с переменными, условиями и циклами.

1. Чем отличается var от let и const?
var имеет функциональную область видимости, тогда как let и const — блочную.
const используется для объявления неизменяемых значений.

2. Что такое неявное преобразование типов в JavaScript?
Это автоматическое преобразование типов данных при выполнении операций (например, сравнение строки и числа).

3. Чем отличается == от ===?
== сравнивает значения с приведением типов,
=== сравнивает значения и типы без преобразования.

# Вывод

В результате лабораторной работы были изучены основы языка JavaScript, способы выполнения кода и базовые конструкции языка, что является фундаментом для дальнейшего изучения веб-программирования.


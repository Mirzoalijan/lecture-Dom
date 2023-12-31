"# lecture-Dom" 
## ЧТО ТАКОЕ DOM?
```
Объектная модель документа: структурированное представление HTML-документов позволяет JavaScript получать доступ к элементам и стилям HTML для управления ими.
```

## DOM
```js
Согласно объектной модели документа (сокращенно DOM), каждый HTML-тег является объектом. 
Подтеги являются «дочерними» родительского элемента. Текст, который находится внутри тега, также является тегом
объект. Все эти объекты доступны с помощью JavaScript, мы можем использовать их для изменения страницы.
```

```js
JavaScript может изменять все элементы HTML на странице.
JavaScript может изменять все атрибуты HTML на странице.
JavaScript может изменять все стили CSS на странице.
JavaScript может удалять существующие элементы и атрибуты HTML.
JavaScript может добавлять новые элементы и атрибуты HTML.
JavaScript может реагировать на все существующие HTML-события на странице.
JavaScript может запускать новые HTML-события на странице
```

```js
Определение и использование. Метод querySelector() возвращает первый дочерний элемент, соответствующий значению 
указанные CSS-селектор(ы) элемента, метод querySelectorAll() можно использовать для доступа ко всем элементам 
которые совпадают с указанным селектором CSS.
```
## Методы массива
```js
innerHTML - Это свойство предоставляет простой способ полностью 
заменить содержимое элемента. Например, все содержимое 
элемента body может быть удалено:
document.body.innnerHTML = ""
```
```js
Объект Style представляет 
Индивидуальное заявление о стиле.
Например:
Element.style.color = "red"
Element.style.color = "red"
Element.style.backroundColor = "black"
```

## Html-события 
```js
HTML-событие может быть чем-то вроде 
Браузер делает или что-то, что делает пользователь.
Вот несколько примеров HTML-событий:
•Веб-страница HTML завершила загрузку.
•Изменено поле ввода HTML.
•Была нажата HTML-кнопка
```

## HTML-элемент DOM appendChild()
```js
Метод appendChild() добавляет узел (элемент) в качестве последнего
дочерний элемент элемента.
appendChild() добавляет узел в конец списка дочерних элементов 
указанный родительский узел. Если данный дочерний элемент является ссылкой на 
существующий узел в документе, а затем appendChild() 
функция перемещает его из текущего положения в новое
```

```js
// Create a p element:
const para = document.createElement("p");
// Create a text node:
const node = document.createTextNode("This is a paragraph.");
// Append text node to the p element:
para.appendChild(node);
// Append the p element to the body:
document.getElementById("myDIV").appendChild(para);

```
## classlist()
```js
ClassList — это геттер. Объект, который он возвращает, имеет несколько методов:
```

```js
add( String [,String] ) 
Добавляет указанные классы к элементу
remove( String [,String] ) 
Удаляет указанные классы из элемента
toggle(String[, Boolean]) 
Если элемент не имеет класса, он добавляет его, в противном случае он удаляет. Когда
false передается в качестве второго параметра, он удаляет указанный
, и если true, он добавляет его.
Если второй параметр не определен или является переменной с
typeof == 'undefined', поведение такое же, как при передаче только тега
Первый параметр при вызове
```

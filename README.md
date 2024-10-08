# Lean_HTML
### Этапы анализа данных и сферы его применения

Сегодня на уроке мы познакомимся с основами веб-разработки, рассмотрим понятия HTML, Frontend и Backend, а также изучим основные HTML-теги, которые используются для создания веб-страниц.

#### Что такое Frontend и Backend?

💡 **Frontend** — это внешняя часть сайта, которую пользователь видит и с которой взаимодействует (например, кнопки, ссылки, формы, текст, фото, видео и аудио материалы).  

💡 **Backend** — это внутренняя часть сайта, отвечающая за его функциональность и работу. Backend включает в себя процессы авторизации пользователей, взаимодействие с базами данных и другие аспекты, определяющие работу сайта в целом.

#### HTML в веб-разработке

💡 **HTML (Hyper Text Markup Language)** — стандартный язык разметки для создания веб-страниц. С его помощью можно структурировать содержимое веб-страницы, задавать заголовки, абзацы, ссылки, изображения и другие элементы.

Чтобы начать работать с HTML в Python, необходимо создать отдельный файл. Это можно сделать двумя способами:
- **webPy → New → HTML File**: автоматически создается шаблон.
- **webPy → New → File**: укажите имя файла как `index.html`, и для создания шаблона пропишите `!` и нажмите `Tab`.

#### Основные HTML-теги

Теги — это ключевые слова, используемые для описания и структурирования содержимого веб-страницы.

- **Одинарные теги**: не имеют закрывающего тега. Пример: `<hr>`.
- **Парные теги**: имеют начало и конец, например, `<h1>...</h1>`.

#### Базовая структура HTML-документа

HTML-документ состоит из следующих основных частей:

- **`<!doctype html>`**: указывает браузеру, какая версия HTML используется.
- **`<html>`**: корневой элемент, содержащий всё содержимое страницы.
- **`<head>`**: раздел документа с метаданными (например, кодировка, описание страницы).
- **`<body>`**: содержит контент, отображаемый на странице.
  
Пример HTML-документа:

```html
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Первый сайт</title>
</head>
<body>
</body>
</html>
```

#### Виды HTML-тегов

1. **Блочные теги**: структурируют основные части страницы, занимают всю ширину сайта. Пример: `<h1></h1>`.
2. **Строчные теги**: применяются для стилизации части текста, не вызывая переноса строки. Пример: `<span></span>`.

Примеры работы с тегами:

```html
<h1>Заголовок 1 уровня</h1>
<p>Это обычный текст параграфа</p>
<span>Текст строчный</span>
<hr>
<p>Текст после горизонтальной линии</p>
<br>
<p>Текст с переносом строки</p>
```

#### Основные теги для работы с ссылками

- **Тег `<a>`**: используется для создания гиперссылок.
- **Атрибут `href`**: задает адрес ссылки.
- **Атрибут `target="_blank"`**: открывает ссылку в новой вкладке.

Пример:

```html
<a href="https://example.com" target="_blank">Этот текст является ссылкой</a>
```

#### Основные теги для работы с контентом

- **Тег `<img>`**: предназначен для отображения изображений на странице.
- **Тег `<video>`**: для встраивания видео.
- **Тег `<audio>`**: для встраивания аудиоконтента.

Примеры:

```html
<img src="path/to/image.jpg" width="300px" alt="Описание изображения">
<video src="path/to/video.mp4" controls loop></video>
<audio src="path/to/audio.mp3" controls muted></audio>
```

#### Списки в HTML

- **Маркированный список** создается с помощью тега `<ul></ul>`.
- **Нумерованный список** — с помощью тега `<ol></ol>`.

Примеры:

```html
<ul>
    <li>Первый пункт списка</li>
    <li>Второй пункт списка</li>
</ul>

<ol>
    <li>Первый пункт списка</li>
    <li>Второй пункт списка</li>
</ol>
```

#### Основные теги для работы с таблицами

- **Тег `<table>`**: используется для создания таблиц.
- **Тег `<tr>`**: определяет строку таблицы.
- **Тег `<td>`**: определяет ячейку таблицы.

Пример таблицы:

```html
<table border="1">
    <tr>
        <th>Название фильма</th>
        <th>Жанр</th>
        <th>Оценка на кинопоиске</th>
    </tr>
    <tr>
        <td>Вонка</td>
        <td>Мюзикл</td>
        <td>7.2/10</td>
    </tr>
    <tr>
        <td>Дюна</td>
        <td>Фантастика</td>
        <td>7.2/10</td>
    </tr>
    <tr>
        <td>Интерстеллар</td>
        <td>Научная фантастика</td>
        <td>8.8/10</td>
    </tr>
</table>
```

#### Итоги урока

Сегодня мы:

- Узнали, что такое HTML и как он используется в веб-разработке.
- Научились создавать простой HTML-документ.
- Ознакомились с основными HTML-тегами и их использованием.

**Дополнительные материалы:**

- [Стоковые аудио](https://stock.adobe.com/ru/audio)
- [Стоковые видео](https://ru.freepik.com/videos)
- [Стоковые фото](https://ru.freepik.com/popular-photos)
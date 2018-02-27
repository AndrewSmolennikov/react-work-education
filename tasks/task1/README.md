# Настроить окружуние

### Задание

* Подготовить директорию для проекта
* Настроить package.json, поставить все зависимые пакеты через npm/yarn 
* Создать директории для исходников и результирующего кода
* Настроить конфигурацию webpack для сборки javascript/typescript кода в отедльный файд
* Настроить конфигурацию webpack для сборки стилей в отедльный файд
* Создать index.css со следующим наполнением
* ```css
  html, bode {
    margin: 0;
    padding: 0;
  }

  h1{
    text-transform: uppercase;
    font-family: arial;
  }
  ```
* Создать index.js/ts со следующим наполнением

* ```js
  var theDiv = document.getElementById("root");
  var h1 = document.createElement("h1");
  h1.innerText = 'Hello, World';
  theDiv.appendChild(h1);
  ```
* Создать \_index.html со следующим наполнением
* ```html
  <!DOCTYPE html>
  <html lang="ru">

    <head>
      <meta charset="utf-8">
      <title>Task 1</title>
    </head>
    <body>
      <div id="root"></div>
    </body>
  </html>
  ```

### Стек

* NodeJS
* Javascript/Typescript
* webpack

### Помощь и советы

* [npm](https://docs.npmjs.com)
* [yarn](https://yarnpkg.com/en/docs)
* [инцилизация package.json](https://docs.npmjs.com/cli/init)
* Не надо комитеть папки node\_modules и build/dist/wwwroot

### Результат

После запуска сборки webpack в директории build/dist/wwwroot должен появится index.html c автоматически созданными ссылками на index.js и index.css


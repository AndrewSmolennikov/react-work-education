# Настройка окружения

### Задание

В данном уроке, необходимо подготовить рабочую директори и настроить package.json с помощью npm. После настройки первых шагов можно приступить к конфигурации webpack для сборки кода на typescript и css стилей, сборка должна происходить в отдельный файл. Для того чтобы проверить работу сборки создадим файлы, который будут собираться.

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
* Создать index.ts со следующим наполнением

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
* Typescript
* webpack

### Помощь и советы

* [документация по npm](https://docs.npmjs.com)
* [документация по yarn](https://yarnpkg.com/en/docs)
* [помощь в настройке package.json](https://docs.npmjs.com/cli/init)
* Разделяйте dependencies и devDependencies
* Не надо комитеть папки node\_modules и build/dist/wwwroot

### Результат

После запуска сборки webpack в директории build/dist/wwwroot должен появится index.html c автоматически созданными ссылками на index.js и index.css. Если запустить index.html то должна появится текст HELLO, WORLD


# Расширенная настройка окружения + погружение в React

### Задание

В данном задание необходимо доработать нашу конфигурацию webpack, а именно нужно:

1. Разделять webpack конфигурацию на prod и dev
2. Минфицировать js и css файлы для prod 
3. Научится опредлять константы в конфигурации webpack для использования их в нашем коде
4. Настроить webpack-dev-server для dev
5. Настроить создание всех source-map для dev

Необходимо переписать наш код из предыдущего задания

```js
  var theDiv = document.getElementById("root");
  var h1 = document.createElement("h1");
  h1.innerText = 'Hello, World';
  theDiv.appendChild(h1);
```

### Стек

* NodeJS
* Typescript
* TSX
* webpack

### Помощь и советы

* За основу можно взять исходники из первого задания

### Результат

после  \[name\].\[chunkhash\].\[ext\] и vendor


# Расширенная настройка окружения + погружение в React

### Задание

В данном задание необходимо доработать нашу конфигурацию webpack, а именно нужно:

1. Разделить webpack конфигурацию на prod и dev
2. Минфицировать js и css файлы для prod 
3. Опредлить константу isDev в конфигурации webpack для использования их в коде
4. Настроить webpack-dev-server для dev
5. Настроить создание всех source-map для dev
6. Настроить очистку директории build/dist/wwwroot перед каждой новой сборкой

Необходимо переписать typescript код из предыдущего задания с использованием React, за место ~~**Hello, world**~~ необходимо вывести на экран **Is {lang} code**, где на основание переменной isDev должно подставится значение:

| isDev | {lang} |
| :--- | :--- |
| true | typescript |
| false | javascript |

### Стек

* NodeJS
* Typescript
* TSX
* webpack

### Помощь и советы

* За основу можно взять исходники из первого задания
* Разделяйте dependencies и devDependencies
* Не надо комитеть папки node\_modules и build/dist/wwwroot

### Результат

После запуска сборки webpack для prod в директории build/dist/wwwroot должы появится файлы index.\[chunkhash\].js, vendor.\[chunkhash\].js, index.\[chunkhash\].css, Если запустить index.html то должен появится текст **IS JAVASCRIPT CODE. **Если запустить webpack в dev, то весь код будет скомпилирован в память, а в консоли появится ссылка [http://localhost:8080](http://localhost:8080),  перейдя по которой можно будет увидеть текст **IS TYPESCRIPT CODE**


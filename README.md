# novell

A simple Vue.js project for HSE

Пункт 1 уже выполнен на компьютерах в HSE

1) Установка nodejs и npm: 

Для Windows / macOS: [Windows / macOS](https://nodejs.org/en/download/)

Для Linxu - открываем терминал, туда вводим:
``` bash
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.9/install.sh | bash

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```
2) Устанавливаем vue-cli:
``` bash
npm i -g vue-cli
```

3) Создаём проект с помощью vue-cli:
``` bash
vue init webpack #название проекта
```

Например:
``` bash
vue init webpack my_super_novell
```

4) Переходим в папочку с проектом:
``` bash
cd #название проекта
```

## Среда разработки

Создавать веб-проеты можно в
 
IDE: WebStorm или Pycharm

Редакторах Atom / Visual Studio Code

## Запуск проекта
``` bash
# установка зависимостей - первая команда
npm install

# запуск разработки и дев-сервера localhost:8080
npm run dev

# собрать проект для размещения на сервере
npm run build

# собрать проект и создать отчёт
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

# Tell Engine
Tell Engine это игровой движок на языке JavaScript, призванный стать помощником для авторов интерактивных историй. Tell Engine работает на основе историй, написанных с помощью инструмента BranchTrack (официальный сайт: [https://branchtrack.com/](https://branchtrack.com/)). В данной документации рассматриваются основные возможности движка, а также приводится пример реализованной на нём истории.

Для полноценного использования движка Вам необходимо иметь базовые знания в HTML5, CSS3, JavaScript, ReactJS.

## Запуск приложения
Склонируйте проект и перейдите в директорию `tell-engine`. Затем, используйте описанные ниже команды для запуска или сборки Вашего приложения.

### `npm run webpack-dev`
Запускает webpack devServer на базе которого будет запущено ваше приложение. Откройте [http://localhost:3000](http://localhost:3000), чтобы взглянуть на проектируемое приложение.

### `npm run webpack-prod`
 Запускает сборку production-версии Вашего приложения. Все исходные файлы, картинки, шрифты будут помещены в директорию `dist` для дальнейшей загрузки на файловый хостинг (например, Вы можете использовать GitHub | Pages).

## Документация
Подробнее о RaactJS Вы можете прочесть здесь: [React documentation](https://reactjs.org/).
Исчерпывающая документация по [Webpack](https://webpack.js.org/concepts/).
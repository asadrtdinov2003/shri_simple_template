<h1>readme<h1>

В этом репозитории находятся материалы для выполнения домашнего задания по темам "Сборка проекта" и "Инфраструктура для разработки".

Это проект приложения на JavaScript, которое представляет собой todo-list (список дел). Приложение позволяет добавлять в список новые элементы и отмечать элементы списка как выполненные.

Вам необходимо сделать форк этого репозитория и выполнить следующие задания:

1. **Подключите в проект инструменты для разработки и настройте их запуск через секцию scripts в package.json**

   - `build` — cборка приложения для публкации в production в папку `dist`
   - `start` — запуск локального сервера для разработки
   - `lint:js` — проверка JS кода при помощи [ESLint](https://eslint.org)
   - `lint:css` — проверка CSS кода при помощи [Stylelint](https://stylelint.io)
   - `analyze` — формирование html отчета о сборке при помощи [Statoscope](http://statoscope.tech)
   - `validate` — проверка сборки через Statoscope при помощи конфига из файла `statoscope.config.js`
   - `deploy` — публикация приложения, собранного командой `build`, в GitHub Pages при помощи пакета [gh-pages](https://www.npmjs.com/package/gh-pages)

2. **Настройте автоматическое выполнение действий в CI**
   - при коммитах в открытые PR запускайте сборку и линтеры кода
   - при влитии PR в основную ветку публикуйте текущую версию приложения в GitHub Pages

   В качестве платформы CI используйте [GitHub Actions](https://docs.github.com/en/actions).

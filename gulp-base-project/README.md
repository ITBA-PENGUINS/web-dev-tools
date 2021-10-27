# Базова структура проекту Gulp
## Як використовувати?
1. Встановити [Node.js](https://nodejs.org/)
2. Скачати файли з цього каталогу. (Використовувати [GitZip](http://kinolien.github.io/gitzip/) або подібні сервіси)
3. Розпакувати вміст архіву у папку проекту і відкрити її у VSCode (або іншому IDE).
3. В терміналі запустити команду `npm install`, після чого необхідні пакети почнуть скачуватись. 
5. Виконати команду `gulp` в терміналі. Вона починає спостереження за вихідними файлами проекту та запускає live server на localhost.
6. Всі вихідні файли проекту знаходяться у каталозі `src/`.
7. Коли проект готовий потрібно запустити команду `gulp build` для збірки production версії, файли якої будуть розміщені у каталозі `dist/`.


# Base project on Gulp
## How to use?
1. Install [Node.js](https://nodejs.org/)
2. Download files from this folder. (Use [GitZip](http://kinolien.github.io/gitzip/) or similar services)
3. Unzip to project folder and open this folder in VSCode (or other IDE).
3. In terminal run a command `npm install` and packages start downloading. Wait for the end of downloading.
5. Run command `gulp`. It starts watching fo projects source files and runs live server on localhost.
6. All source project files located in `src/` folder.
7. When project is ready, run `gulp build` for build production version, project files will be located in `dist/` folder.

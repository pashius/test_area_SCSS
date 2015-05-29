# Испытательный полигон для экспериментов с SCSS

Испытательный полигон для работы с препроцессором SCSS.



## Как начать:

### 1. Установить [Git](http://git-scm.com/), [Node.js](http://nodejs.org/) и [Grunt](http://gruntjs.com/)

Git после первого занятия на продвинутом интенсиве HTML Academy у Вас уже установлен, а без Node.js и Grunt (или Gulp) сложно представить себе технологический процесс создания современного фронтэнда.



### 2. Открыть консоль и перейти в папку, отведенную для Ваших проектов

Запустить консоль и набрать команду перехода к папке, в которой хранятся все проекты. К примеру: `cd my_projects\github\`

Для пользователей Windows, не сталкивавшихся ранее с консолью, лучше скачать и установить [cmder](http://bliker.github.io/cmder/) (эмулятор консоли).

Пользователям Windows: для перехода на другой диск нужно сначала набрать букву диска (например: `D:`) и нажать <kbd>Enter</kbd>. Потом выполнить команду `cd` для перехода в нужную папку. В cmder достаточно набрать пару первых символов имени папки и нажать <kbd>Tab</kbd>, чтобы получить полное имя папки.



### 3. Клонировать этот репозиторий

1. В консоли перейти в ту папку, где Вы храните все свои проекты.
2. Скопировать адрес этого репозитория на гитхабе. 
3. Ввести в консоли команду `git clone тут_адрес_этого_зепозитория тут_имя_папки`. Последняя часть этой команды — имя папки, куда будет клонирован этот репозиторий. Этой папки ещё нет, она будет создана.



### 4. Установить плагины Grunt

Перейти в папку, имя которой Вы вписали выше, набрав `cd тут_имя_папки`. Ввести (скопировать-вставить) в консоли  команду `npm i`, дождаться окончания загрузки и установки компонентов. В папке с проектом появится папка 'node_modules', в которую скачались все нужные плагины.



### 5. Запустить Grunt

В консоли (находясь в папке проекта) нужно ввести (скопировать-вставить) команду `grunt`. При этом запустится слежение за файлами, автокомпиляция файлов препроцессора (по изменению любого препроцессорного файла), автообновление страницы при изменениях файлов препроцессора или HTML-файлов. Если компиляция препроцессорного файла прервется с ошибкой, Grunt сообщит об этом в консоли.

Чтобы остановить слежение, нужно нажать в консоли <kbd>Ctrl</kbd>+<kbd>C</kbd>

Если Вы добавляете файлы препроцессора, не перезапуская слежения, изменения в этих файлах не будут вызывать компиляцию CSS.



## Как убедиться, что всё работает

Запустите слежение за файлами командой `grunt`.

Измените что-либо в файлах препроцессора (значение переменной с размером шрифта) и взгляните на открытый html-файл — должна произойти автоперезагрузка страницы с новыми стилями.
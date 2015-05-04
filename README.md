##Пустой Шаблон для верстки##

###Директории###

app/- директория разработки проекта  
    |_ css/ - готовый css для проекта
    |_ fonts/ - шрифты для проекта
    |_ images/ - изображения
        |_ favicon/ - содержит фавикон для проекта
    |_ jade/ - папка для препроцессора jade, структурировано  в виде модулей.
    |_ js/ - js 
        |_ libs/ - подключаемые компоненты js
        |_ maine.js - основной js код тут, в виде модулей  
    |_ sass/ - для препроцессора, использовать модульную структуру, каждый логический блок свой sass файл.(так же подключен bourbon)  
    |_ index.html


gulpfile.js - исполняемый файл галпа.  
package.json - кофигурация галпа.
    |_"gulp": "^3.8.10",
    |_""gulp-autoprefixer": "^2.1.0",
    |_""gulp-cache": "^0.2.4",
    |_""gulp-cached": "^1.0.2",
    |_""gulp-concat-css": "^2.1.2",
    |_""gulp-connect": "^2.2.0",
    |_""gulp-jade": "^0.11.0",
    |_""gulp-livereload": "^3.2.0",
    |_""gulp-load-plugins": "^0.8.0",
    |_""gulp-minify-css": "^0.5.0",
    |_""gulp-notify": "^2.1.0",
    |_""gulp-rename": "^1.2.0",
    |_""gulp-sass": "^1.3.3",
    |_""gulp-util": "^3.0.3",
    |_""opn": "^1.0.1",
    |_""wiredep": "^2.2.2"
bower.json - конфигурация bower.
.bowerrc - конфигурация папки, куда bower складывает компоненты.
.gitignore - сюда вносятся файлы которые не заливаются в репозиторий  
###Инициализация проекта###

Для начала работы необходимо склонировать себе репозиторий,  
далее в консоли выполнить npm install, а также bower install.



 Make love, not war  

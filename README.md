Данный проект создаваося в учебных целях. Он представляет собой облако для хранения файлов с определенными расширениями.


Для развертывания сервера на локальном хосте использовался OSPanel, директория /.osp настраивает модули

ВАЖНО: Обратите внимание, что команды для разных частей приложения запускаются строго из сответствующих папок (/api - для сервера и /client - для клиентской части)

Для скачивания необходимых зависимостей в серверной части использовать команду: 
    composer install

Для запуска сервера: 
    php artisan serve --port:8000

Для скачивания необходимых библиотек и зависимостей используйте команду: 
    yarn

Для запуска клиентской части используется команда: 
    yarn dev

ps: Для того, чтобы открыть документацию необходимо запустить сервер и перейти по ссылке:
    http://localhost:8000/docs/index.html

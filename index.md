---
layout: default
---

Cloud Commander 0.8.2 [![NPM version][NPMIMGURL]][NPMURL] [![Dependency Status][DependencyStatusIMGURL]][DependencyStatusURL] [![Build Status][BuildStatusIMGURL]][BuildStatusURL] [![License][LicenseIMGURL]][LicenseURL] [![Flattr][FlattrIMGURL]][FlattrURL]
===============
###[Головна][MainURL] [Блог][BlogURL] Наживо(![IO][IO_LIVE_IMG] [IO][IOURL], ![JitSu][JitSu_LIVE_IMG] [JitSu][JitSuURL], ![Heroku][Heroku_LIVE_IMG] [Heroku][HerokuURL])
[NPMIMGURL]:                https://img.shields.io/npm/v/cloudcmd.svg
[BuildStatusIMGURL]:        https://img.shields.io/travis/coderaiser/cloudcmd/dev.svg
[DependencyStatusIMGURL]:   https://gemnasium.com/coderaiser/cloudcmd.png
[FlattrIMGURL]:             https://img.shields.io/badge/flattr-donate-317BF9.svg
[LicenseIMGURL]:            https://img.shields.io/badge/license-MIT-317BF9.svg
[NPM_INFO_IMG]:             https://nodei.co/npm/cloudcmd.png?downloads=true&&stars
[NPMURL]:                   http://badge.fury.io/js/cloudcmd
[BuildStatusURL]:           https://travis-ci.org/coderaiser/cloudcmd  "Build Status"
[DependencyStatusURL]:      https://gemnasium.com/coderaiser/cloudcmd "Dependency Status"
[FlattrURL]:                https://flattr.com/submit/auto?user_id=coderaiser&url=github.com/coderaiser/cloudcmd&title=cloudcmd&language=&tags=github&category=software "flattr"
[LicenseURL]:               https://tldrlegal.com/license/mit-license "MIT License"
[NPM_INFO_URL]:             https://npmjs.org/package/cloudcmd "npm"
[MainURL]:                  http://cloudcmd.io "Головна"
[BlogURL]:                  http://blog.cloudcmd.io "Блог"
[DemoURL]:                  http://io.cloudcmd.io "Демо"
[IOURL]:                    http://io.cloudcmd.io "IO"
[JitSuURL]:                 http://cloudcmd.jit.su "JitSu"
[HerokuURL]:                http://cloudcmd.herokuapp.com/ "Heroku"
[IO_LIVE_IMG]:              http://status-ok.cloudcmd.io/host/io.cloudcmd.io/fs?json "IO"
[JitSu_LIVE_IMG]:           http://status-ok.cloudcmd.io/host/cloudcmd.jit.su/fs?json "JitSu"
[HEROKU_LIVE_IMG]:          http://status-ok.cloudcmd.io/host/cloudcmd.herokuapp.com/fs?json "Heroku"

**Cloud Commander** - хмарний файловий менеджер з консоллю та редактором.

![Cloud Commander](http://cloudcmd.io/img/logo/cloudcmd.png "Cloud Commander")

Переваги
---------------
- Відкритий код.
- Має дві класичні панелі.
- Працює під Windows, Linux та Mac OS.
- Може використовуватись локально або віддалено.
- Має гарну консоль та редактор.
- Написаний на JavaScript/Node.js.
 
Встановлення
---------------

**Cloud Commander** встановлюється дуже просто:

- встановити [node.js](http://nodejs.org/ "node.js").
- встановити ```cloudcmd``` через npm за допомогою однієї простої команди.

![NPM_INFO][NPM_INFO_IMG]

Гарячі клавіші
---------------

- **F1**                - допомога
- **F2**                - змінити назву обраного файлу
- **F3**                - переглянути
- **F4**                - редагувати
- **F5**                - копіювати
- **F6**                - змінити назву/перемістити
- **F7**                - нова папка
- **F7** + **shift**    - новий файл
- **F8, Delete**        - знищити обраний файл
- **F9**                - меню
- **F10**               - налаштування
- **(*)**               - виділити/зняти виділення з усього
- **(+)**               - розширити виділення
- **(-)**               - звузити виділення
- **Ctrl + r**          - оновити вміст папки
- **Ctrl + d**          - очистити локальний кеш, що містить вміст папки
- **Alt  + q**          - вимкнути прив'язку клавіш
- **Alt  + s**          - відновити усі прив'язки клавіші
- **Ctrl + a**          - виділити усі файли на панелі
- **up, down, enter**   - пересування файловою систему
- **Ctrl + \**          - перейти до кореневого каталогу
- **Tab**               - переміщення між панелями
- **Page Up**           - вгору на одну сторінку
- **Page Down**         - вниз на одну сторінку 
- **Home**              - на початок списку 
- **End**               - в кінець списку
- **Shift + Delete**    - знищити підтвердження
- **Insert**            - обрати поточнний файл
- **Shift + F10**       - контекстне меню
- **~**                 - консоль
- **Ctrl + Click**      - відкрити файл в новій вкладці

Редактор
---------------
[Демо](http://io.cloudcmd.io/fs/etc#/edit/passwd "Edit")
![Edit](http://cloudcmd.io/img/screen/edit.png "Edit")


###Гарячі клавіші
- **F4**                - відкрити
- **Ctrl + s**          - зберегти
- **Esc**               - закрити
 
Детальніше [Гарячі клавіші Ace](https://github.com/ajaxorg/ace/wiki/Default-Keyboard-Shortcuts "Гарячі клавіші Ace").

Консоль
---------------
[Демо](http://io.cloudcmd.io#/console "Консоль")
![Консоль](http://cloudcmd.io/img/screen/console.png "Консоль")

###Гарячі клавіші
- **~**                 - відкрити
- **Esc**               - закрити

Налаштування
---------------
[Демо](http://io.cloudcmd.io#/config "Налаштування")
![Налаштування](http://cloudcmd.io/img/screen/config.png "Налаштування")

###Гарячі клавіші
- **F10**               - відкрити
- **Esc**               - закрити

Меню
---------------
[Демо](http://io.cloudcmd.io#/menu "Меню")
![Menu](http://cloudcmd.io/img/screen/menu.png "Меню")
Натискання на праву клавішу мишки, викликає меню з наступними пунктами:

- Перегляд
- Редагування
- Змінити назву
- Знищити
- Zip файл
- Обрати все
- Вивантажити до (Dropbox, Github, GDrive)
- Завантажити
- Новий (Файл, Папка, з хмари)
 
###Гарячі клавіші
- **F9**                - відкрити
- **Esc**               - закрити

Налаштування
---------------
Всі головні налаштування можна встановити в config.json.

```js
{
    "auth"              : false,    /* дозволити http авторизацію                                   */
    "username"          : "root",   /* ім'я користувача для авторизації                             */
    "password"          : "toor",   /* пароль хеш в sha-1 для авторизації                           */
    "apiURL "           :"/api/v1",
    "appCache"          : false,     /* кешувати файли для оффлайнового використання                */
    "analytics"         : true,      /* підтримка google analytics                                  */
    "diff"              : false,     /* при збереженні - відсилає патч, а не повний файл            */
    "notifications"     : false,     /* показувати сповіщення, коли вкладка не активна              */
    "localStorage"      : true,      /* кешування вмісту папки                                      */
    "minify"            : true,      /* мініфікація js,css,html та зображень                        */
    "cache"             : true,      /* додати контроль кешу                                        */
    "online"            : true,      /* загрузити файли js з cdn або Local path                     */
    "logs"              : false,     /* виводити в логи чи в консоль                                */
    "showKeysPanel"     : true,      /* показати класичну панель з кнопками функціональних клавіш   */
    "server"            : true,      /* режим сервера чи тестування                                 */
    "socket"            : true       /* увімкнути web сокети                                        */
    "port"              : 8000,      /* http порт                                                   */
    "sslPort"           : 443,       /* https порт                                                  */
    "ip"                : null,      /* ip чи null(за замовчуванням)                                */
    "ssl"               : false      /* використовувати https?                                      */
    "rest"              : true       /* увімкнути решту інтерфейса                                  */
}
```

Якщо ви змінили **config** і хочете продовжувати оновлюватись за допомогою git,
вам потрібно виконати наступну команду в кореневій директорії **Cloud Commander**:

```
git update-index --assume-unchanged json/config.json
```

Щоб повернутися до відстежування:

```
git update-index --no-assume-unchanged json/config.json
```

Сервер
---------------
Зазвичай процеси, що запущено правами не root не можуть звертатися до портів нижче ніж 1024.
В любому випадку, Я раджу Вам запускати Cloud Commander не під рутом. Як це зробити?!
Існує декілька простих і швидких шляхів. Один з них - просування портів через iptables.

###Iptables
Просто запустіть [shell/addtables.sh](http://github.com/coderaiser/cloudcmd/blob/master/shell/addtables.sh) для стандартних опцій.

```sh
@:/tmp/cloudcmd (dev) $ sudo iptables -t nat -L # look rules before
@:/tmp/cloudcmd (dev) $ sudo iptables -t nat -A PREROUTING -p tcp --dport 80 -j REDIRECT --to-ports 8000
@:/tmp/cloudcmd (dev) $ sudo iptables -t nat -A PREROUTING -p tcp --dport 443 -j REDIRECT --to-ports 4430
@:/tmp/cloudcmd (dev) $ sudo iptables -t nat -L # look reles after
```
Ви маєте побачити щось таке ( **8000** та **4430** мають бути в config як **port** і **sslPort** )

    target     prot opt source               destination
    REDIRECT   tcp  --  anywhere             anywhere             tcp dpt:http redir ports 8000
    REDIRECT   tcp  --  anywhere             anywhere             tcp dpt:https redir ports 4430

Якщо захочете все повернути, просто очистіть правила ( **1** та **2** це номера правил,
у вашому випадку вони можуть відрізнятися).

```sh
@:/tmp/cloudcmd (dev) $ sudo iptables -t nat -D PREROUTING 1
@:/tmp/cloudcmd (dev) $ sudo iptables -t nat -D PREROUTING 2
```

###nginx
Візьміть [nginx](http://nginx.org/ "nginx"). В linux це можна зробити наступним чином:

```sh
sudo apt-get install nginx #for ubuntu and debian
```

І зробіть хост файл **/etc/nginx/sites-enabled/io.cloudcmd.io**
( *io.cloudcmd.io* ваше доменне ім'я) з вмістом:

```sh
server {
    listen 80;
    client_max_body_size 100m;
    server_name io.cloudcmd.io;
    access_log /var/log/nginx/io.cloudcmd.io.access.log;
    location / {
        proxy_pass    http://127.0.0.1:8000/;
    }
}
```

Якщо ви бажаєте додати **ssl**, додайте декілька рядків в розділ серверу:

```sh
server {
    listen 443;
    client_max_body_size 100m;
    ssl                  on;
    ssl_certificate      /home/coderaiser/cloudcmd/ssl/ssl.crt;
    ssl_certificate_key  /home/coderaiser/cloudcmd/ssl/ssl.key;
    server_name io.cloudcmd.io;
    access_log /var/log/nginx/io.cloudcmd.io.access.log;
    location / {
        proxy_pass    http://127.0.0.1:8000/;
    }
}
```

Якщо вам потрібне перенаправлення з **http** до **https**, просто зробіть так:

```sh
server {
    listen 80;
    server_name admin.cloudcmd.io;
    rewrite ^ https://io.cloudcmd.io$request_uri? permanent; #301 redirect
    access_log /var/log/nginx/io.cloudcmd.io.access.log;
}
```

```sh
# create symlink of this file
ln -s ./sites-enabled/io.cloudcmd.io ./sites-available
# restart nginx
/etc/init.d/nginx restart
```

Для запуску Cloud Commander під daemon в linux встановіть **log** в "істину" в config-файлі і
зробіть щось на зразок:
    
    nohup node cloudcmd

Запуск
---------------
Для запуску **Cloud Commander** потрібна лише одна команда:
    
    node cloudcmd
або на Windows

    cloudcmd

Після цього, Cloud Commander читає інформацію порта з файлу налаштувань [config.json](http://github.com/coderaiser/cloudcmd/blob/master/json/config.json#L17) і запускає сервер
на цьому порті ( **8000**, за замовчуванням ),якщо змінних портів не існує( *cloud9*, *cloudfoundry* and *nodester* ).
Тоді просто наберіть в броузері

    http://127.0.0.1:8000
або

    http://localhost:8000
    
Оновлення
---------------
**Cloud Commander** дуже часто оновлюється.
Оновлення відбувається автоматично, але його можна виконати власноруч
за допомогою декількох команд в папці Cloud Commander:

    git pull
перевірити наявність нової версії на npm

    npm info cloudcmd

і якщо нова версія існує

    npm r cloudcmd
    npm i cloudcmd

Список додаткових модулів
---------------
Щоб розширити функціонал файлового менеджера, використано такі модулі:

- [Ace]                     [AceURL]
- [FancyBox]                [FancyBoxURL]
- [jQuery-contextMenu]      [jQuery-contextMenuURL]
- [jq-console]              [jq-consoleURL]
- [github]                  [githubURL]
- [dropbox-js]              [dropbox-jsURL]
- [jquery]                  [jqueryURL]
- [socket.io]               [socketIOURL]
- [http-auth]               [httpAuthURL]
- [fs-extra]                [fs-extraURL]

[AceURL]:                   http://ace.ajax.org/ "Ace"
[FancyBoxURL]:              //github.com/fancyapps/fancyBox "FancyBox"
[jQuery-contextMenuURL]:    //github.com/medialize/jQuery-contextMenu "jQuery-contextMenu"
[jq-consoleURL]:            //github.com/replit/jq-console "jq-console"
[githubURL]:                //github.com/michael/github "github"
[dropbox-jsURL]:            //github.com/dropbox/dropbox-js "dropbox-js"
[jqueryURL]:                //jquery.com
[socketIOURL]:              http://socket.io
[httpAuthURL]:              //github.com/gevorg/http-auth
[fs-extraURL]:              //github.com/jprichardson/node-fs-extra "fs-extra"

Долучитися до проекту
---------------
Якщо ви хочете долучитися до проекту - відправте pull запит в dev гілку.
Отримання dev версії **Cloud Commander**:

    git clone git://github.com/coderaiser/cloudcmd.git
    git checkout dev

Можливо вам знадобиться dev версія Minify,
щоб отримати її, вам потрібно ввести декілька команд:

    cd node_modules
    rm -rf minify
    git clone git://github.com/coderaiser/minify
    git checkout dev

Історія версій
---------------
- *2014.xx.xx*, **[v0.9.0](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.9.0.zip)**
- *2014.03.03*, **[v0.8.2](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.8.2.zip)**
- *2014.02.13*, **[v0.8.1](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.8.1.zip)**
- *2014.02.13*, **[v0.8.0](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.8.0.zip)**
- *2013.12.09*, **[v0.7.0](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.7.0.zip)**
- *2013.11.08*, **[v0.6.0](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.6.0.zip)**
- *2013.10.17*, **[v0.5.0](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.5.0.zip)**
- *2013.09.27*, **[v0.4.0](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.4.0.zip)**
- *2013.08.01*, **[v0.3.0](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.3.0.zip)**
- *2013.04.22*, **[v0.2.0](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.2.0.zip)**
- *2013.03.01*, **[v0.1.9](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.1.9.zip)**
- *2012.12.12*, **[v0.1.8](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.1.8.zip)**
- *2012.10.01*, **[v0.1.7](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.1.7.zip)**
- *2012.08.24*, **[v0.1.6](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.1.6.zip)**
- *2012.08.06*, **[v0.1.5](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.1.5.zip)**
- *2012.07.27*, **[v0.1.4](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.1.4.zip)**
- *2012.07.19*, **[v0.1.3](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.1.3.zip)**
- *2012.07.14*, **[v0.1.2](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.1.2.zip)**
- *2012.07.11*, **[v0.1.1](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.1.1.zip)**
- *2012.07.09*, **[v0.1.0](//github.com/cloudcmd/archive/raw/master/cloudcmd-v0.1.0.zip)**

Щира подяка:
---------------
- [Polietilena](http://polietilena.github.io/ "Polietilena") за [логотип](http://cloudcmd.io/img/logo/cloudcmd.png "логотип") так [favicon](http://cloudcmd.io/img/favicon/favicon.png "favicon");
- [TarZak](https://github.com/tarzak)
    - [російский](http://ru.cloudcmd.io "Cloud Commander російскою") та [український](http://ua.cloudcmd.io "Cloud Commander українською") переклади;
    - налаштування: [шаблон](html/config.html) та [стилі](css/config.css);

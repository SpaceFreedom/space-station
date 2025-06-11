Space Freedom - форк WWDP, представляющего из себя хард-форк  [Space Station 14](https://github.com/space-wizards/space-station-14).
Space Station 14 - это ремейк SS13, который работает на собственном движке  [Robust Toolbox](https://github.com/space-wizards/RobustToolbox), собственном игровом движке, написанном на C#.
Поскольку это хард-форк, любой код, взятый из другого апстрима, не может быть напрямую замержен сюда, а должен быть перенесен.

## Ссылки
[Steam](https://store.steampowered.com/app/2585480/Space_Station_Multiverse/) | [Клиент без Steam](https://spacestationmultiverse.com/downloads/) | [Основной репозиторий](https://github.com/Simple-Station/Einstein-Engines)

## Контрибуция
В процессе разработки, ожидайте новостей!

## Сборка
Следуйте [гайду от Space Wizards](https://docs.spacestation14.com/en/general-development/setup/setting-up-a-development-environment.html) по настройке рабочей среды, но учитывайте, что наши репозитории отличаются и некоторые вещи могут отличаться.
Мы предлагаем несколько скриптов, показанных ниже, чтобы облегчить работу.

### Необходимые зависимости
> - Git
> - .NET SDK 9.0.101


### Windows
> 1. Склонируйте данный репозиторий
> 2. Запустите `git submodule update --init --recursive` в командной строке, чтобы скачать движок игры
> 3. Запускайте `Scripts/bat/buildAllDebug.bat` после любых изменений в коде проекта
> 4. Запустите `Scripts/bat/runQuickAll.bat`, чтобы запустить клиент и сервер
> 5. Подключитесь к локальному серверу и играйте

### Linux
> 1. Склонируйте данный репозиторий.
> 2. Запустите `git submodule update --init --recursive` в командной строке, чтобы скачать движок игры
> 3. Запускайте `Scripts/sh/buildAllDebug.sh` после любых изменений в коде проекта
> 4. Запустите `Scripts/sh/runQuickAll.sh`, чтобы запустить клиент и сервер
> 5. Подключитесь к локальному серверу и играйте

### MacOS
> Предположительно, также, как и на Линуксе.

## Лицензия
Содержимое, добавленное в этот репозиторий, распространяется по лицензии GNU Affero General Public License версии 3.0, если не указано иное.
См. [LICENSE-AGPLv3](./LICENSE-AGPLv3.txt).

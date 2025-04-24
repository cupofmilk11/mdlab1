Первый мой проект на Флаттер.

Установка Flutter:
Был установлен Flutter на ПК, следуя инструкции с официального сайта Install | Flutter.
Это включало загрузку и распаковку архива Flutter SDK, а также настройку пути к нему в системе.

Установка расширения Flutter в VS Code:
В VS Code было установлено расширение Flutter через маркетплейс.

Установка Android Studio:
Android Studio была установлена исключительно для настройки Android SDK и эмулятора. Использовал официальный сайт Download Android Studio & App Tools - Android Developers.
После установки Android Studio, через SDK Manager были установлены необходимые компоненты Android SDK.

Добавление Flutter в переменные среды Windows:
Путь к Flutter SDK был добавлен в системные переменные среды Windows, чтобы команды Flutter могли выполняться из любой директории в командной строке.

Проверка окружения с помощью flutter doctor:
В командной строке была выполнена команда flutter doctor, которая показала ошибку: Android SDK не был найден.

Указание пути к Android SDK:
С помощью команды flutter --android-sdk "<путь-к-sdk>" был указан путь к Android SDK, чтобы Flutter мог его использовать.

Повторная проверка flutter doctor:
После указания пути к SDK, команда flutter doctor показала, что в Android SDK отсутствуют cmdline-tools, а также не были приняты некоторые лицензии.

Установка cmdline-tools:
Через SDK Manager в Android Studio были установлены cmdline-tools, необходимые для работы Flutter с Android SDK.

Принятие лицензий:
Лицензии Android SDK были приняты с помощью команды flutter doctor --android-licenses.

Финальная проверка flutter doctor:
После всех настроек команда flutter doctor показала отсутствие ошибок.

Создание проекта Flutter:
В VS Code был создан новый проект Flutter типа "Application" с помощью команды Shift + Ctrl + P => flutter: new project.
Были указаны имя проекта и путь для его сохранения.

Выбор устройства для запуска:
Через команду Shift + Ctrl + P => flutter: select device был выбран эмулятор устройства "Google Pixel 5".
Эмулятор был запущен для тестирования приложения.

Запуск проекта:
Проект был запущен с помощью клавиши F5. Приложение успешно запустилось на эмуляторе, и появился стандартный экран Flutter-приложения с текстом "You have pushed the button this many times:".

Инициализация Git и создание первого коммита:
В VS Code была открыта встроенная поддержка Git.
Через вкладку Source Control (или нажав Ctrl + Shift + G) был инициализирован Git в папке проекта.
Все файлы были добавлены в индекс (staged), и создан первый коммит с сообщением "Initial commit".

Публикация репозитория на GitHub через VS Code:

В разделе Source Control была нажата кнопка "Publish to GitHub".
После авторизации в GitHub через VS Code был создан новый репозиторий с именем 1-md_1lab.
Проект был успешно опубликован по адресу.

1. git init

Ёта команда используетс€ дл€ инициализации проекта как репозитори€ git.


2. git clone

Ёта команда клонирует репозиторий в новую директорию. 

git config Ч это удобна€ функци€, котора€ используетс€ дл€ настройки значений конфигурации Git на глобальном и локальном уровн€х проекта. ѕримеры команд:

git config --local user.name "Name"

git config --local user.email "your_email@example.com"

 git config --global user.name "Name"

 git config --global user.email "your_email@example.com"


≈сли надо скопировать только файлы:

git clone --depth=1 git://someserver/somerepo dirformynewrepo

rm -rf !$/.git
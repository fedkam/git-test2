# git-test2
Тест ссылок на другие gitrep
https://git-scm.com/book/en/v2/Git-Tools-Submodules

git clone --recurse-submodules nameURL клонирование\инитПодМодулей\ОбновлениеПодМодулей <br>

git submodule add nameURL<br>

git submodule init<br>
git submodule update --remote _nameSubmodule

Команды для полного удаления git сабмодуля:<br>
Удалить секцию модуля из .gitmodules<br>
Выполнить команду git add .gitmodules<br>
Удалить модуль из .git/config<br>
Выполнить команду git rm -rf --cached path_to_submodule чтобы удалить директорию из индекса<br>
Выполнить команду rm -rf .git/modules/path_to_submodule<br>
Выполнить коммит git commit -m "Removed submodule <name>"<br>
Выполнить команду rm -rf path_to_submodule чтобы удалить "неотслеживаемые" файлы подмодуля<br>

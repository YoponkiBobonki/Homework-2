# Подсказки по командной строке

команда смены директаров 

```sh
cd c:/folder_name
```
Команда отображающей текущей директории
```sh
pwd
```
Листинг текущий директории
```sh
dir
```
Удаление файла в Виндовс
```sh
del<filename>
```
посмотреть лог в сокращенном виде 
```sh
git log --oneline
```

Перемещение по веткам 
```sh
git checkout <branch_name>
```

создать ветку
```sh
git branch <branch_name>
```
Удаление ветки
```sh
git branch -d <имя_ветк>
```
Смотреть лог в графическом виде
```sh
git log --oneline --graph
```
Если хотите посмотреть полный график то можно сделать так:
```sh
git log --graph
```

Иногда после конфликта не получится удалить ветку через **git branch -d** в этом случае нужно использовать эту команду
```sh
git branch -D <name_branch>
```

> не знаю еще что добавить поэтому хочу спросить когда я пишу *git log*  мне показывает последние две коммита, а остальных нет. как можно это исправить или это так и должно быть ?) 

# инструкция по GIthub

Команда git clone используется для копирования существующего репозитория с GitHub (или другого удаленного хостинга) на ваш локальный компьютер.
```sh
git clone
```
Команда git push отправляет коммиты из вашего локального репозитория в удаленный репозиторий
```sh
git push
```
Команда git pull используется для получения последних изменений из удаленного репозитория и их слияния с вашей локальной копией.
```sh
git pull
```
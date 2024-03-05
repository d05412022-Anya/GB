## Создание репозитория
```sh
git init
```
## Проверка состояния
```sh
git status
```

## Добавить файл к отслеживанию
```sh
git add
```
## Добавить коммит с сообщением
```sh
git commit -m"message"
```
## Лог всех коммитов
```sh
git log
```
## Лог коммитов упрощённый
```sh
git log --oneline
```
## Лог коммитов с графическим отображением ветвей
```sh
git log --oneline --graph
```
## Команда для переключения между коммитами, ветвями
```sh
git checkout <name>
```
## Показать существующие ветви
```sh
git branch
```
## Добавить новую ветвь 
*branch_new - название новой ветви*
```sh
git branch branch_new
```
## Слияние веток 
*в ветке master, указывать **сливаемую** ветку*
```sh
git merge branch_new
```
## Удаление ветки
```sh
git branch -d<branch_name>
```

## Создание репозитория
```sh
git init
```
## Проверка состояния
```sh
git status
```
## Лог всех коммитов
```sh
git log
```
## Лог коммитов упрощённый
`
git log --oneline --graph
### Список коммитов упрощённый сокращенный
```sh
git log --oneline
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
git branch branch_name
```
## Слияние веток 
*в ветке master, указывать **сливаемую** ветку*
```sh
git merge branch_new
```
## Удаление ветви
```sn
git branch -d<branch_name>
```

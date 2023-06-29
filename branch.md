# git branch #

## Что делает ##
Эта команда может немного больше, чем просто в git создавать ветки из текущей.
***

## Пример ##
```shell
$ git branch
```
При выполнении этой строки мы получим список существующих веток, где символом * будет отмечена ветка, где вы сейчас находитесь. Это может выглядеть так:
```shell
$ git branch

  first_branch
* master
  second_branch
```
***
```shell
$ git branch -v
```
С помощью параметра -v можно получить последний сохраненный коммит в каждой ветке.
```shell
$ git branch -v

  first_branch 9fg301b fix text
* master 225cc2d Merge branch 'first_branch'
  second_branch l56ee12 fix code style
```

[Назад в Главное меню](README.md)

# Как переименовать ветку

В процессе разработки могут возникнуть ситуации, когда человек хочет по-другому называть уже созданную ветку. 
Это может быть связано с разными причинами (например, разрабатываемый в данной версии функционал не соответствует названию). 
Чтобы переименовать ветку применяем:

```shell
$ git branch -m <my_first_branch_name>
```
Где `<my_second_branch_name>` новое ваше название ветки.

Однако здесь нужно быть аккуратными, чтобы не перегрузить проект ненужными ветками. Если запушить переименованную ветку, то на сервере появится ветка с новым именем, но и ветка со старым названием тоже останется. Чтобы избежать такой проблемы, необходимо удалить ветку локально и на сервере.

[Назад в Главное меню](README.md)

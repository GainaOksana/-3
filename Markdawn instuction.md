# Инструкция для работы с Markdown
git init - создание репозитория.

git add - добавить фаел к отслеживанию.

git commit -m "" сохранение текущего состояния

git diff - контроль изменений

git log - журнал изменений

git branch - знакомство с ветками

git branch и название новой ветки (создание ччерновика)


## Выделение текста
Чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например, *вот так* или _вот так_.

Что бы выделить текст полужирным необходимо обрамить его двумя звездочками (**) или двойным знаком нижнего подчеркивания (__). Например, **вот так** или __вот так__.

Альтернативные способы выделения текста выделения жирным или курсивом нужны для того что бы мы могли совмещать оба этих способа. Например, _текст может быть выделн курсивом и при этом быть **полужирным**_.


## Cписки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкий (*). Например, вот так:

* Элемент 1
* Элемент 2
* Элемент 3

Чтобы добывить нумерованные списки, необходимо пункты просто пронумеровать. Например, вот так:

1. Первый пункт
2. Второй пункт


## Работа с изображениями

Чтобы вставить изображение в текс, достаточно написать следующее:
![Привет](123.png)

## Ссылки

## Работа с таблицами

## Цитаты

## Заключение

# Работа с GitHub

# create a new repository on the command line
echo "# -3" >> README.md

  git init
  
  git add README.md
  
  git commit -m "first commit"
  
  git branch -M main
  
  git remote add origin https://github.com/GainaOksana/-3.git
  
  git push -u origin main

# …or push an existing repository from the command line
git remote add origin https://github.com/GainaOksana/-3.git

  git branch -M main
  
  git push -u origin main

# …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

git push - выгрузка изменений в Git Hub


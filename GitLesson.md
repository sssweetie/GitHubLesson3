# Инструкция для работы с Markdown

## Выделение текста

Чтбы выделить текст курсивом небходимо обрамить его звездочками (*). 
Например, *вот так*

Чтобы выделить текст полужирным, необходимо обрамить его двойной 
звездочкой (**) или двойным знаком нижнего подчеркивания (__). 
Например, **вот так** или __вот так__.

Альтернатива нужна, чтобы совмещать написания одного текста. 
Например: *__вот так__*! 

~~текст~~ - зачеркнутый текст ~ c двух сторон


## Списки

Чтобы выделить не нумерованный список используйте (*) или знаком +
Например, вот так:
* Элемент
* Элемент
* Элемент
+ Элемент


Чтобы добавить не нумерованные списки, необходимо пункты выделить 
цифрой.
Например, вот так:
1. Элемент
2. Элемент
3. Элемент

Основный моменты выглядят подобным образом

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следующее:
![На арте старый добрый винил!](3840x1080-Wallpaper-064-768x216.jpg)

## Ссылки

1. https://habr.com/ru/post/541258/ - материалы для новичков часть 1

2. https://habr.com/ru/post/542616/ - материалы для новичков часть 2

3. https://training.github.com/downloads/ru/github-git-cheat-sheet/ - памятка с ресурса GitHub


## Работа с таблицами

1. Вы можете создавать таблицы с вертикальной чертой | и дефисами -. Дефисы используются, чтобы создать для каждого столбца заголовок. Вертикальные черты разделяют столбцы. Необходимо включить пустую строку перед таблицей, чтобы она правильно преобразовалась для просмотра.Чтобы включить вертикальную черту | ​​в качестве содержимого в вашу ячейку, используйте \ перед вертикальной чертой:

| Command| Description| Comments |
| --- | --- | --- | 
| touch | create new file |
| mkdir | create new repositoriy |

2. Текст можно выровнять по левому, правому краю или по центру столбца, включив двоеточия : слева, справа или с обеих сторон от дефисов в строке заголовка.

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

3. В таблице можно использовать форматирование, например ссылки, встроенные блоки кода и оформление текста:

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

4. Чтобы включить вертикальную черту | ​​в качестве содержимого в вашу ячейку, используйте \ перед вертикальной чертой:

| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |



## Базовые команды

* **ctrl + schift + ~** - open terminal

* **git init** - initializing empty git repository

Initialization of an empty git repository (if the repository has already been initialized, you do not need to do this action again) Initialization of an empty git repository (if the repository has already been initialized, you do not need to do this action again)

* **git status** - show untracked files 

* **git add** - add file version

* **git add .** - add version to all files 

* **git commit** - save changes 

* **git commit -m** - allow us to avoid git console and type message inside terminal

* **git commit -am "message"** - the same as flag -m but allow us avoid git add

* **ctrl + 1** - code

* **ctrl + 0** - file tree

* **git log** - get story of commits 

* **git log --oneline** - get shortstory of commits 

* **git checkout** - allow us switch commits

* **git checkout master** - get back to main tree

* **git diff** - show difference between current state and last commit

* **git branch** - show the list of branches

- **git branch branch_name** - create a new branch

- **git branch -d branch_name** - delete merged branch

- **git branch -D branch_name** - force deleting branch

## Удаленный репозиторий

- **git clone [link or GitHub code]** - copy to yourself the local version of the remote repository

- **git remote** - view the list of configured remote repositories

- **git remote -v** - view read and write addresses linked to the repository

- **git fetch [remote-name]** - he team contacts the specified remote project and takes all the project data that you don't have yet

- **git push <remote-name> <branch-name>** - send changes to a remote repository

- **git remote show <remote-name>** - This command shows which local branch will be sent to the remote server by default when performing git push

- **git pull <remote-name> <branch-name>** - download changes to yourself from remote repository

- **git remote rm** - delete remote repository

## Цитаты

## Заключение 

reset!
Homework_2 version_1!




And merge them again.
Homework_2 version_1

And merge them.
Line 4 is ready to action!)

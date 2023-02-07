
# Git instructions (briefly) / инструкция к Гит (кратко)

**git init** -- initializing empty git repository / инициализация пустого гит-репозитория (если репозиторий уже инициализирован, то повторно это действие делать не нужно)

**git status** -- show untracted files / показывает изменения в файлах в сравнении с сохраненной версией

### **git add** -- add file version / добавляет изменения в локальный репозиторий

* **git add .** -- add version to all files / добавить версию всех файлов, которые есть (либо указать путь к конкретному файлу)

### **git commit** -- save changes / фиксация изменений 
* **git commit -m "message"** -- allow us to avoid git console and type message inside terminal / позволяет нам сохранять комментарии к изменениям в строке
* **git commit -am "message"** -- the same as flag -m but allow us avoid git add / флаг, подобный -m, но позволяет нам избежать добавления в гит

**git log** -- get story of commits  / выводит перечень всех изменений

**git checkout** -- allow us switch commits / позволяет перемещаться между сохранениями (между коммитами)

**git diff** -- show differences between current and last commit / показывает разницу между текущей и зафиксированной версией

**git branch** -- show  branches / показывает перечень всех веток 

**git branch new_branch_name** -- create new branch / создает новую ветку в дереве

**git checkout master** -- get back to main tree / возвращает обратно в основную ветку дерева

**git checkout other_branch_name** -- get back to other branch / переход в названную ветку дерева

**git merge branch_name** -- delete    / вливание названной ветки в основную (на которой стоим)

**git branch -d branch_name** -- delete merging branch / удаление слитой ветки

**git branch -D branch_name** -- delete  unmerging branch  / удаление неслитой ветки

**git branch -b branch_name** -- create a new branch and immediately switch to it  / создаем новую ветку и сразу переключаемся на нее

**git log --graph**  --  show commit's tree (graphic)  / визуализация дерева комитов

**cd ..**  --  go to the top-level folder  / переход на папку верхнего уровня

**cd <.\NameFolder\>**  --  go to the specified folder  / переход на указанную папку 

## Работа с удаленными репозиториями 

* **git clone <url-адрес репозитория>** -- cloning an external repository to a local computer / клонирование внешнего репозитория на локальный ПК

* **git pull** -- getting changes and merging with the local version / получение изменений и слияние с локальной версией

* **git push** -- send the local version of the repository to the external one / отправляем локальную версию репозитория на внешний

* **git fetch** -- extracting data from a remote repository / извлечение данных из удаленного репозитория

# Markdown instructions (briefly) / инструкция к Markdown (кратко)

## ***Titles and lists/ заголовки и списки***

* ### Title --    the selection of titles, the number of characters (#) sets the level of the title - up to 6 levels / выделение заголовков, количество символов (#) задает уровень заголовка - до 6 уровней

* line   --   unordered lists, character '*' at the beginning of the line / ненумерованные списки, символ  в начале строки

* 1,2,3, --  numbered lists (dotted digit) / нумерованные списки (пишем цифру с точкой)

1. 
2.

## ***Show text / Отображение текста***

*  **bold font**   or/или    __полужирное начертание__    --    bold font / полужирное начертание

*  italics*    or/или     _курсивное начертание_    --    italics / курсивное начертание

* ***bold italics***     --   bold italics / полужирное курсивное начертание

* = or/или -     -- underlining these characters (at least 3 in a row) highlight the headings of the first ("=") and second ("-") levels / подчеркиванием этими символами (не менее 3 подряд) выделяют заголовки первого ("=") и второго ("-") уровней

* ~~strikethrough text~~    --    strikethrough text / зачеркнутый текст

* Hello <sub>This is subscript!</sub>   -- subscript / подстрочный текст

* Goodbye <sup>This is superscript!</sup>   -- superscript / надстрочный текст

## ***Table / Таблицы***

|This is   |a simple   |table header|
|----------|-----------|------------|
|**table**     |data       |here        |
|**it doesn't**|actually   |have to line up nicely!|

## ***Citations and references / Цитирование и ссылки***

> This is a blockquote   --  It is usually rendered indented and with a different background color / Это блок цитирования, обычно он отображается с отступом и имеет другой цвет фона

* **<!--- Here's my comment --->**   -- undisplayed comment / комментарий, который не отображается

![alt text for image](../images/Introduction.png)   - add an image and text to it / добавляет изображение и текст к нему

* https://learn.microsoft.com/<locale>/<product-service>/[<feature-service>]/[<subfolder>]/<topic>[?view=<view-name>]     -- typical link construction / типовая конструкция ссылки

* https://learn.microsoft.com/azure/load-balancer/load-balancer-overview   -- link example / пример ссылки

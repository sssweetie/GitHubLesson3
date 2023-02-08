GIT#3 - система контроля версий.
=====================================
[😎Качественный и понятный скринкаст](https://vimeo.com/showcase/5616060)\
**pull request** - запрос на изменения\
при изменении чужого репозитория лучше создать отдельную ветку\
|**README.MD**| usually called using capslock
>`git fetch` загружает удаленное содержимое, но не изменяет состояние local repo, в то время как git pull загружает удаленное содержимое и сразу пытается изменить состояние local repo.
## Commands:
### GitHub / Working with a remote repository
- `git push` - added files the remote repository
- `git pull` - get files the remote repository and make merge with local repo
- `git fetch` - get files the remote repository without changes for local repo
- `git clone https://github.com/` - clone the remote repository
    >use `git clone https://github.com/ newFolder` copy to a specific folder
-------------------------------------------------
### Algorithm of working with foreign _(чужой)_ repository 
1. touch on **fork** 
2. clone the **forked** repository
3. create a new branch for working (зависит от проекта)
4. push the our **forked** repository
5. run **pull request** and wait... :D
---
## Dictionary:
1. **origin** - происхождение, начало, источник
1. **request** - просьба, запрос
1. **usually** - обычно, обыкновенно
1. **specific** - конкретный, определенный
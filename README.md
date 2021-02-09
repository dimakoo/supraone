# лабораторная работа Колесникова Дмитрия
PS C:\Users\User\dimako> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitconfig
        README.md

nothing added to commit but untracked files present (use "git add" to track)
```
```
S C:\Users\User\dimako> git add README.md
PS C:\Users\User\dimako> git status README.md
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
```
git commit  
Обнаружен своп-файл с именем "C:/Users/User/dimako/.git/.COMMIT_EDITMSG.swp"
          владелец: User    дата: 07 фев 2021 Вс 12:32:16
         имя файла: ~User/dimako/.git/COMMIT_EDITMSG
           изменён: ДА
      пользователь: User  компьютер: DESKTOP-T6GNTP0
           процесс: 1559 (ВЫПОЛНЯЕТСЯ)
при открытии файла: "C:/Users/User/dimako/.git/COMMIT_EDITMSG"
              дата: 09 фев 2021 Вn 19:54:31
                    Более СВЕЖИЙ, чем своп-файл!
(1) Возможно, редактирование этого же файла выполняется в другой программе.
    Если это так, то будьте внимательны при внесении изменений, чтобы
    у вас не появилось два разных варианта одного и того же файла.
    Выйдите или продолжайте с осторожностью.
(2) Сеанс редактирования этого файла завершён аварийно.
    В этом случае, используйте команду ":recover" или "vim -r C:/Users/User/dimako/.git/COMMIT_EDITMSG"
    для восстановления изменений (см. ":help recovery").
    Если вы уже выполняли эту операцию, удалите своп-файл "C:/Users/User/dimako/.git/.COMMIT_EDITMSG.swp"
    чтобы избежать появления этого сообщения в будущем.

Своп-файл "C:/Users/User/dimako/.git/.COMMIT_EDITMSG.swp" уже существует!
[O] Открыть для чтения, (E) Редактировать, (R) Восстановить, (Q) Выход, (A) Прервать: 
```
```
git commit -m "мой первый коммит"
>> 
[master (root-commit) 6e33b27] мой первый коммит
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
```
```
git remote
pb
```
```
git checkout
M       README.md
```
```
git checkout README.md
Updated 1 path from the index
```
```
git stash 
No local changes to save
```
```
git stash pop
No stash entries found.
```
```
git branch ветка2
git checkout ветка2
Switched to branch 'ветка2'
```
```
PS C:\Users\User\dimako> git checkout master
Switched to branch 'master'
PS C:\Users\User\dimako> git merge ветка2
Already up to date.
```
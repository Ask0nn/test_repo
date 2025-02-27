## Основные команды Git  

* git init – инициализация локального репозитория
* git status – получить информацию от git о его текущем состоянии
* git add – добавить файл или файлы к следующему коммиту
* git commit -m “message” – создание коммита.
* git log – вывод на экран истории всех коммитов с их хеш-кодами
* git checkout – переход от одного коммита к другому
* git checkout master – вернуться к актуальному состоянию и продолжить работу
* git diff – увидеть разницу между текущим файлом и закоммиченным файлом

    ![Тут должна быть картинка](./assets/index.png)

> С цитатами сложна.


[Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637)

## Работа с удаленными репозиториями

* git clone <URL> – Клонирование удаленного репозитория на локальную машину. Выполняет полное копирование удаленного репозитория, включая все коммиты, ветки и файлы.  
* git pull – Получение и объединение изменений из удаленного репозитория в текущую ветку локального репозитория. Эта команда обновляет локальную ветку и автоматически пытается объединить ее с удаленной веткой.  
* git push – Отправка изменений из локального репозитория в удаленный репозиторий. Эта команда загружает все коммиты, которых нет в удаленной ветке, и обновляет удаленную ветку.
* git fetch – Получение всех изменений из удаленного репозитория без объединения с локальной веткой. Команда загружает все коммиты, ветки и файлы, которых нет в локальном репозитории.
* git branch -r – Просмотр списка удаленных веток. Эта команда показывает все ветки, которые существуют в удаленном репозитории.
* git branch -a – Просмотр списка всех локальных и удаленных веток. Эта команда показывает все ветки, как локальные, так и удаленные.
* git remote add <имя> <URL> – Добавление нового удаленного репозитория. Вы можете использовать это, чтобы установить связь с другим репозиторием и легко отправлять и получать изменения.
* git remote -v – Просмотр списка всех удаленных репозиториев, связанных с вашим локальным репозиторием. Эта команда показывает URL-адреса для чтения и записи каждого удаленного репозитория.
* git remote remove <имя> – Удаление связи с удаленным репозиторием. Эта команда удаляет указанный удаленный репозиторий из вашего локального репозитория.

Это лишь некоторые из основных команд Git для работы с удаленными репозиториями. Существуют и другие команды, которые можно использовать в различных ситуациях, в зависимости от вашей работы с Git.
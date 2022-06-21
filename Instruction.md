## Команда для работы с удаленными репозиториями 

* git clone  составная: она не только загружает все изменения, но и пытается слить   все ветки на локальном компьютере и в удаленном репозитории

* git push  Отправить свою версию репозитория во внешний репозиторий поможет команда git push. При первом её использовании нужна авторизация

* git pull Эта команда позволяет скачать все   из текущего репозитория и автоматически сделать merge с нашей версией 

## Как настроить совместную работу 
1. Создать аккаунт на GitHub.com
2. Создать локальный репозиторий
3. “Подружить” ваш локальный и удалённый репозитории. GitHub при создании нового репозитория подскажет, как это можно сделать
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно,   вам нужно будет авторизоваться на удалённом репозитории 
5. Провести изменения “с другого компьютера” 
6. Выкачать (pull) актуальное состояние из удалённого репозитория

**pull request**

➜ команда для предложения изменений ➜ запрос на вливание изменений в репозиторий В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду pull request. Предлагать изменения на GitHub нужно в отдельной ветке. Сначала пользователь копирует репозиторий на свой компьютер, делает fork репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой push в свой аккаунт на GitHub и даёт команду pull request. 

Как сделать pull request 

1. Делаем fork(ответвление) репозитория fork 
2. Делаем git clone совей версии репозитория 
3. Создаем новую ветку и в НЕЕ вносим свои изменения 
4. Фиксируем изменения (делаем коммиты) 
5. Отправляем свою версию в свой GitHub 
6. На сайте GitHub нажимаем кнопку pull requestКоманда для работы с удаленными репозиториями 

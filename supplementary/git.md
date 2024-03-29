# Руководство по работе с GitHub

## Работа с git

`git version` - проверяем установленную версию

**Первое использование**: указываем имя пользователя и привязанный e-mail

`git config --global user.name "username"`

`git config --global user.email username@example.com`

**Работа с репозиторием**

`git clone https://github.com/username/example.git` - клонируем репозиторий

`git add` - добавляем отслеживание содержимого рабочего каталога

Примеры: `git add .` - отслеживаем все файлы; `git add helloworld.py` - отслеживаем файл "helloworld.py"

`git status` - смотрим, какие изменения произошли

`git reset` - отменяем незафиксированные изменения

`git commit` - фиксируем изменения

Пример: `git commit -m "Add helloworld.py"`

`git push` - отправляем изменения на сервер

Пример: `git push origin main`

**Стандартный процесс**

`git add .`

`git commit -m "Add helloworld.py`

`git push`
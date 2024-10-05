### Learn Git

#### <a name='toc'>Содержание</a>
1. [Создание проекта](#create_project)
2. [Проверка состояния](#checking_status)
3. [Настраиваем клиент NFS](#setting_client)
4. [Автоматизация Vagrant + Ansible](#creating_automated)

#### 1. [[⬆]](#toc) <a name='create_project'>Создание проекта</a>

##### Создайте страницу «Hello, World»
```
mkdir work && cd work
echo "Hello, World" >> hello.html
```

##### Создайте репозиторий
```
git init
```
![image](https://github.com/user-attachments/assets/7660091a-153e-433b-bce6-bcc1194d332f)

##### Добавьте страницу в репозиторий
```
git add hello.html
git commit -m "Initial Commit"
```
![image](https://github.com/user-attachments/assets/449c99ff-f6af-4378-acf8-e65c3a1057ef)

#### 1. [[⬆]](#toc) <a name='checking_status'>Проверка состояния</a>

##### Проверьте состояние репозитория
Используйте команду git status, чтобы проверить текущее состояние репозитория.
```
git status
```
![image](https://github.com/user-attachments/assets/3893b6ae-130a-45af-885d-d2851c03fee2)

Команда проверки состояния сообщила, что коммитить нечего. Это означает, что в репозитории уже хранится текущее состояние рабочих файлов, и нет никаких изменений, которые могли бы ожидать записи.





### Learn Git

#### <a name='toc'>Содержание</a>
1. [Создание проекта](#create_project)
2. [Настраиваем сервер NFS](#setting_server)
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
![image](https://github.com/user-attachments/assets/d3bc4f50-c6de-4cb8-86a7-8042e5c5de69)

##### Добавьте страницу в репозиторий
```
git add hello.html
git commit -m "Initial Commit"
```
![image](https://github.com/user-attachments/assets/fee1a212-a610-4df7-b447-3edd2ed63ab2)



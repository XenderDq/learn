# Инструкция по работе с Git
# Введение
Git — это система контроля версий, которая позволяет отслеживать изменения в файлах и координировать работу нескольких человек над одним проектом.

# Установка Git
Перейдите на официальный сайт Git.
# https://git-scm.com
Скачайте и установите Git для вашей операционной системы.
# Настройка Git
После установки Git, настройте ваше имя и email:


* git config --global user.name "Your Name"
* git config --global user.email "your.email@example.com"

# Создание репозитория

Перейдите на GitHub и войдите в свою учетную запись.
Нажмите на значок "+" в правом верхнем углу и выберите "New repository".
Заполните необходимые поля (название репозитория, описание и т.д.) и нажмите "Create repository".
Клонирование репозитория
После создания репозитория на GitHub, скопируйте URL репозитория. Затем выполните следующую команду в терминале:


* git clone https://github.com/your-username/your-repository.git
Добавление изменений и коммит
Перейдите в директорию репозитория:


* cd your-repository
Добавьте файлы и сделайте коммит:


* git add .
* git commit -m "Initial commit"
Отправка изменений на GitHub
Отправьте изменения на GitHub:


* git push origin main
Работа с ветками
Если вы хотите создать новую ветку и отправить изменения в нее:


* git checkout -b new-branch-name
* git add .
* git commit -m "Your commit message"
* git push origin new-branch-name

# Переключение между ветками

Чтобы переключиться на другую ветку:


* git checkout existing-branch-name
Просмотр всех веток
Чтобы увидеть все существующие ветки:


* git branch
Пример рабочего процесса
Создание репозитория на GitHub.

Клонирование репозитория на локальную машину:


* git clone https://github.com/your-username/your-repository.git
# Переход в директорию репозитория:


* cd your-repository
# Добавление и коммит изменений:


* git add .
* git commit -m "Initial commit"
# Отправка изменений на GitHub:


* git push origin main
# Создание новой ветки и отправка изменений:


* git checkout -b feature-branch
* git add .
* git commit -m "Add new feature"
* git push origin feature-branch
# Переключение на другую ветку:


* git checkout main
# Пример проекта
# Вот пример структуры проекта:


my-project/
├── index.html
├── css/
│   └── style.css
├── images/
│   └── 200.png
└── README.md
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <h1>Welcome to My Project</h1>
    <img src="images/200.png" alt="Logo">
</body>
</html>
css/style.css

body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin-top: 50px;
}

h1 {
    color: #333;
}

img {
    width: 200px;
    height: auto;
}

learn/
├── README.md
├── images/
│   └── 200.png


README.md

# My Project

This is a simple project to demonstrate the use of Git and GitHub.

## Features

- HTML file with basic structure
- CSS file for styling
- Logo image

### Заархивированный проект

Вы можете скачать заархивированный проект [здесь](https://example.com/my-project.zip).

---

Надеюсь, эта инструкция поможет вам начать работу с Git и GitHub. Если у вас возникнут вопросы, не стесняйтесь задавать их!
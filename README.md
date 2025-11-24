# hallo.github.io
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Git — короткий курс</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #24292e;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            border-left: 5px solid #ff9900;
            padding-left: 10px;
        }
        pre {
            background: #eee;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .certificate {
            border: 2px dashed #ff9900;
            padding: 20px;
            text-align: center;
            background: #fff7e6;
            margin: 20px 0;
        }
        footer {
            text-align: center;
            margin-top: 30px;
            color: #555;
        }
    </style>
</head>
<body>

<header>
    <h1>Огляд Git та основи роботи</h1>
</header>

<div class="container">
    <h2>1. Коротка інформація про системи контролю версій та Git</h2>
    <p>Система контролю версій (VCS) — це інструмент, що дозволяє відстежувати зміни у файлах, зберігати історію та працювати над проєктом у команді. Git — найпопулярніша сучасна система контролю версій, створена Лінусом Торвальдсом у 2005 році. Вона дозволяє ефективно працювати над програмними проєктами, підтримує розподілений підхід та забезпечує високу швидкість роботи.</p>

    <h2>2. Основні можливості та переваги Git</h2>
    <ul>
        <li>Розподілена система — кожен користувач має повну копію репозиторію.</li>
        <li>Висока швидкість обробки операцій.</li>
        <li>Надійна система збереження історії.</li>
        <li>Гнучка робота з гілками (branches).</li>
        <li>Велика екосистема та інтеграція з GitHub, GitLab, Bitbucket.</li>
    </ul>

    <h2>3. 10 базових команд Git</h2>
    <pre>
1. git init — створення нового репозиторію.
2. git clone URL — клонує віддалений репозиторій.
3. git status — показує статус файлів.
4. git add . — додає файли до індексу.
5. git commit -m "текст" — створює коміт.
6. git push — надсилає зміни у віддалений репозиторій.
7. git pull — отримує та зливає зміни.
8. git branch — перегляд/створення гілок.
9. git checkout branch — перехід до іншої гілки.
10. git merge branch — злиття гілки з поточною.
    </pre>

    <h2>4. Сертифікат курсу</h2>
    <div class="certificate">
        <h3>Сертифікат</h3>
        <p>Даний документ підтверджує успішне опрацювання базового курсу по Git.</p>
    </div>

    <h2>5. Джерела інформації</h2>
    <ul>
        <li>Офіційна документація: https://git-scm.com/</li>
        <li>GitHub Guides: https://guides.github.com/</li>
        <li>Pro Git Book</li>
    </ul>
</div>

<footer>
    <p>Автор: Богдан</p>
</footer>

</body>
</html>

---
title: Посібник для початківців
author: Krista Burdine
contributors: Ezequiel Bruni, Steven Spencer, Ganna Zhyrnova
tags:
  - сприяння
  - документація
  - новачки
  - howto
---

# Посібник для новачків

*Кожен з чогось починає. Якщо ви вперше робите свій внесок у документацію з відкритим кодом на GitHub, вітаємо з цим кроком. Нам не терпиться побачити вашу думку!* Для найкращих результатів ознайомтеся з [нашим посібником зі стилю](style_guide.md), який містить посилання на кілька інших документів, що допоможуть вам ознайомитися з найкращими практиками документування.

## Git і GitHub

Усі наші інструкції для учасників передбачають наявність облікового запису GitHub. Якщо ви ніколи цього не робили, зараз саме час. Якщо у вас є 12 хвилин, дізнайтеся основи GitHub за допомогою [Посібника Git і GitHub для початківців](https://www.udacity.com/blog/2015/06/a-beginners-git-github-tutorial.html) від Udemy.

Можливо, ви не починаєте зі створення та керування репозиторіями для Rocky Linux, але цей [посібник Hello World](https://docs.github.com/en/get-started/quickstart/hello-world) проведе вас через створення облікового запису GitHub, вивчення термінології та розуміння того, як працюють репозиторії. Зосередьтеся на вивченні того, як створювати та фіксувати оновлення в існуючих документах, а також на тому, як створити Pull Request.

## Markdown

Markdown — це проста мова, яка дозволяє включати форматування, код і звичайний текст в один файл. Під час першого оновлення документа дотримуйтеся існуючого коду. Незабаром ви будете готові досліджувати додаткові функції. Коли прийде час, ось основи.

- [Базовий Markdown](https://www.markdownguide.org/basic-syntax#code)
- [Розширений Markdown](https://www.markdownguide.org/extended-syntax/#fenced-code-blocks)
- Деякі з додаткових параметрів [розширеного форматування](https://docs.rockylinux.org/guides/contribute/rockydocs_formatting/), які ми використовуємо в нашому сховищі

## Редактор локального сховища

Щоб створити локальне сховище, спершу знайдіть і встановіть редактор Markdown, який працює з вашим комп’ютером і операційною системою. Ось деякі варіанти, але є й інші. Використовуйте те, що знаєте.

- [ReText](https://github.com/retext-project/retext) – безкоштовний, міжплатформний і відкритий код
- [Zettlr](https://www.zettlr.com/) – безкоштовний, кросплатформний із відкритим кодом
- [MarkText](https://github.com/marktext/marktext) – безкоштовний, міжплатформний і відкритий код
- [Remarkable](https://remarkableapp.github.io/) – Linux і Windows, відкритий код
- [NvChad](https://nvchad.com/) для користувача vi/vim і клієнта nvim. Доступно багато плагінів для вдосконалення редактора для уцінки. Перегляньте [цей документ](https://docs.rockylinux.org/books/nvchad/), щоб отримати чудові інструкції зі встановлення.
- [VS Code](https://code.visualstudio.com/) – частково відкритий код від Microsoft. VS Code — це легкий і потужний редактор, доступний для Windows, Linux і MacOS. Щоб зробити свій внесок у цей проект документів, ви повинні отримати такі розширення: Git Graph, HTML Preview, HTML Snippets, Markdown All in One, Markdown Preview Enhanced, Markdown Preview Mermaid Support та інші, які вам сподобаються.

## Створіть локальне сховище

Після встановлення редактора Markdown дотримуйтесь інструкцій, щоб підключити його до свого облікового запису GitHub і завантажити репозиторій на локальну машину. Кожного разу, коли ви готуєтеся оновити документ, виконайте такі кроки, щоб синхронізувати ваші локальні та онлайн-розгалуження з основною гілкою, щоб переконатися, що ви працюєте з найновішою версією:

1. У GitHub синхронізуйте свою гілку сховища документації з основною гілкою.
2. Дотримуйтеся вказівок редактора Markdown, щоб синхронізувати вашу поточну гілку із локальною машиною.
3. У редакторі Markdown відкрийте документ, який потрібно змінити.
4. Змініть документ.
5. Збережіть його.
6. Закомітте свої зміни у своєму редакторі, який має синхронізувати ваше локальне сховище з вашою онлайн-гілкою.
7. У GitHub знайдіть оновлений документ у своїй гілці та створіть Pull Request, щоб об’єднати його з основним документом.

## Надішліть оновлення

*Додайте пропущене слово, виправте помилку або поясніть заплутаний фрагмент тексту.*

1. Почніть зі сторінки, яку потрібно оновити.

    Натисніть на олівець «Редагувати» у верхньому правому куті документа, який потрібно оновити. Ви перейдете до оригінального документа на GitHub.

    Під час першого внеску в репозиторій RL вам буде запропоновано зелену кнопку «**розщепити** це **репозиторій** і запропонувати зміни». Це створює дублікат репозиторію RL, де ви вносите запропоновані зміни. Просто натисніть зелену кнопку та продовжуйте.

2. Внесіть свої зміни

    Дотримуйтеся форматування Markdown. Можливо, пропущене слово або, наприклад, потрібно виправити посилання в рядку 21. Внесіть необхідні зміни.

3. Запропонуйте зміни

    Унизу сторінки напишіть однорядковий опис у заголовку блоку під назвою «**Запропонувати зміни»**. Це корисно, але не обов’язково посилатися на ім’я файлу, указане у верхній частині документа.

    Отже, якщо ви оновили посилання в рядку 21 тексту розмітки, ви б сказали щось на зразок «Оновіть README.md правильними посиланнями».

    **Примітка: сформулюйте свою дію в теперішньому часі.**

    Потім натисніть «Запропонувати зміни», що **закріпить** ваші зміни до повного документа у вашому розгалуженому сховищі.

4. Перегляньте зміни

    Тепер ви можете переглянути, що ви зробили, рядок за рядком. Ви щось пропустили? Створіть резервну копію попередньої сторінки та знову виправте її (вам доведеться почати спочатку), а потім знову натисніть «Запропонувати зміни».

    Коли документ буде таким, як ви хочете, натисніть зелену кнопку з написом «Створити запит на вилучення». Це дає ще один шанс ще раз перевірити ваші зміни та підтвердити, що документ готовий.

5. Створіть Pull Request

    Усю вашу роботу досі виконували у вашому власному сховищі, без можливості зламати основне сховище RL. Потім ви надсилаєте його групі документації, щоб об’єднати вашу версію в основну версію документа.

    Натисніть велику зелену кнопку з написом Create Pull Request. Хороші новини, ви все ще нічого не зламали, тому що тепер це відправлено на перевірку групі документації RL.

6. Зачекайте

    Коли команда RL отримає ваш запит, вона відповість одним із трьох способів.

    - Прийме і об'єднає ваш PR
    - Прокоментує відгук і попросить внести зміни
    - Відмовить вашому PR з поясненням

    Остання відповідь малоймовірна. Ми дійсно хочемо включити вашу точку зору тут! Якщо вам доведеться внести зміни, ви раптом зрозумієте, навіщо вам локальне сховище. Команда може [пояснити вам](https://chat.rockylinux.org/rocky-linux/channels/documentation), що робити далі. Хороша новина: це все ще можна виправити. Якщо вам потрібно додати або змінити ваш запит на зміщення (pull request), член команди додасть його до розділу коментарів.

    В іншому випадку ваш запит буде прийнято та об’єднано. Ласкаво просимо до команди, тепер ви офіційно учасник! Подивіться, чи за кілька днів ваше ім’я з’явиться у списку всіх співавторів унизу посібника для співавторів.

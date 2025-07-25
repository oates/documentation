---
title: Відстеження та не слідкування за гілками в Git
author: Wale Soyinka
contributors:
tags:
  - git
  - git branch
  - Tracking Branch
  - Non-Tracking Branch
---

## Вступ

Цей Gemstone заглиблюється у відстеження та невідстеження гілок у Git. Він також містить кроки для перевірки та перетворення між типами гілок.

## Tracking Branch

Гілка відстеження – це гілка, пов’язана з віддаленою гілкою.

1. Створіть нову гілку під назвою my-local-branch. Зробіть так, щоб нова локальна гілка відстежувала основну гілку віддаленого сховища з назвою origin. Впишіть:

  ```bash
  git checkout -b my-local-branch origin/main
  ```

2. Використовуйте команду `git branch -vv`, щоб переконатися, що гілка є гілкою відстеження. Впишіть:

  ```bash
  git branch -vv
  ```

  Шукайте гілки з `[origin/main]`, що вказує, що вони відстежують `origin/main`.

## Non-Tracking Branch

Філія без відстеження – це філія, яка працює незалежно від віддалених філій.

1. Створіть нову локальну гілку без відстеження під назвою my-feature-branch. Впишіть:

  ```bash
  git checkout -b my-feature-branch
  ```

2. Гілки без відстеження не відображатимуть віддалену гілку поруч із ними у виводі git branch -vv. Перевірте, чи my-feature-branch є гілкою без відстеження.

## Перетворення невідстеження в відстеження

1. За бажанням, спочатку переконайтеся, що останні зміни з основної гілки об’єднано в цільову гілку. Впишіть:

  ```bash
  git checkout my-feature-branch
  git merge main
  ```

2. Налаштувати відстеження до віддаленого відділення:

  ```bash
  git branch --set-upstream-to=origin/main my-feature-branch
  ```

  Вихід: \`Гілка 'my-feature-branch' налаштована для відстеження віддаленої гілки 'main' від 'origin'.'

3. Перевірте зміну. Впишіть:

  ```bash
  git branch -vv
  ```

  Тепер `my-feature-branch` має показувати `[origin/main]`, що вказує на відстеження.

## Висновок

Розуміння нюансів між відстежуваними та невідстежуваними гілками є життєво важливим у Git. Цей документ пояснює ці концепції, а також демонструє, як ідентифікувати ці типи гілок і конвертувати між ними для оптимального керування робочим процесом git.

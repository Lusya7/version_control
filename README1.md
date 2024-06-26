# Подсказка по GIT
## *Создание репозитория*
~~~sh
git init
~~~

## *Добавление изменений*
~~~sh
git add <file_name>
~~~
## *Просмотр состояния репозитория*
~~~sh
git status
~~~

## *Фиксация, сохранение изменений*
~~~sh
git commit -m "Message"
~~~

## *Просмотр журнала всех изменений*
~~~sh
git log
git log --oneline
~~~

## *Просмотр различий между комитами*
~~~sh
git diff
~~~

## *Просмотр конкретного комита, переключение между ними*
~~~sh
git checkout
~~~

## *Список всех веток*
~~~sh
git branch
~~~

## *Создание новой ветки*
~~~sh
git branch <branch_name>
~~~

## *Просмотр дерева*
~~~sh
git log graph
git log --oneline --graph
~~~

## *Удаление ветки*
~~~sh
git branch -d <branch_name>
~~~

## *Копирование удаленного репозитория*
~~~sh
git clone
~~~

## *Толкаем локальный репозиторий*
~~~sh
git push
~~~

## *Тянем удаленный репозиторий в локальный*
~~~sh
git pull
~~~

## *Выкачка и слияние при конфликте*
~~~sh
git pull --rebase
git rebase --continue
~~~

# Конец подсказки :)))


# Подсказка по Markdown

## *Заголовки*

# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня

# Выделение текста

*Курсив* / _Курсив_

**Жирный** / __Жирный__

***Жирный курсив*** / ___Жирный курсив___

~~Зачеркнутый~~

# Списки

## *Нумерованный список*

1. первый пункт
2. второй пункт
3. третий пункт

## *Маркированный список*

- первый пункт
- второй пункт
- третий пункт

## *Ссылки*

[Текст ссылки](https://ее_адрес)

## *Изображения*

![Текст описания](https://его_адрес)

## *Цитаты*

> первый уровень цитирования
>> второй уровень цитирования
>>> третий уровень цитирования

## *Автоматические ссылки*

<http://example.com>

address@example.com


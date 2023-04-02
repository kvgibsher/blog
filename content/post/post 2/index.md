---
title: Язык разметки MarkDown.
subtitle: Здравствуйте! В данном посте вы можете познакомиться с языком разметки Markdown. Тут представлена самая необходимая и первичная информация для работы с Markdown.

# Summary for listings and search engines
summary: 

# Link this post with a project
projects: []

# Date published
date: '2020-12-13T00:00:00Z'

# Date updated
lastmod: '2020-12-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
 

tags:
  - Academic
  

categories:
  - Тематический пост
 
---

## Язык разметки MarkDown.

Markdown -  это удобный и быстрый способ разметки текста. Маркдаун используют, если недоступен HTML, а текст нужно сделать читаемым и хотя бы немного размеченным (заголовки, списки, картинки, ссылки).

Чтобы создать заголовок, используйте знак #, например:

# This is heading 1
## This is heading 2
### This is heading 3
#### This is heading 4

Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки:

This text is **bold**.

Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:

This text is *italic*.



Чтобы задать для текста полужирное и курсивное начертание, заключите его в тройные звездочки:

This is text is both ***bold and italic***.

Блоки цитирования создаются с помощью символа >:

> The drought had lasted now for ten million years



Упорядоченный список можно отформатировать с помощью соответствующих цифр:

1. First instruction
1. Sub-instruction
1. Sub-instruction
1. Second instruction

Чтобы вложить один список в другой, добавьте отступ для элементов дочернего списка:

1. First instruction
1. Second instruction
1. Third instruction

Неупорядоченный (маркированный) список можно отформатировать с помощью звездочек или тире:

* List item 1
* List item 2
* List item 3


Чтобы вложить один список в другой, добавьте отступ для элементов дочернего списка:

- List item 1
- List item A
- List item B
- List item 2

Синтаксис Markdown для встроенной ссылки состоит из части [link text], представляющей текст гиперссылки, и части (file-name.md) – URL-адреса или имени файла, на который дается ссылка:

[link text](file-name.md)

или

[link text](http://example.com/ "Необязательная подсказка")

Markdown поддерживает как встраивание фрагментов кода в предложение, так и их размещение между предложениями в виде отдельных огражденных блоков. Огражденные блоки кода — это простой способ выделить синтаксис для фрагментов кода.




## Оформление изображений в Markdown



В Markdown вставить изображение в документ можно с помощью непосредственного указания адреса изображения. Синтаксис данной команды выглядит
следующим образом:

( воскл. знак. [Подпись к рисунку](/путь/к/изображению.jpg "Необязательная подсказка"){ #fig:fig1 width=70% }) 
Здесь:

• в квадратных скобках указывается подпись к изображению;
• в круглых скобках указывается URL-адрес или относительный путь изображения, а также (необязательно) всплывающую подсказку, заключённую
в двойные или одиночные кавычки.
• в фигурных скобках указывается идентификатор изображения (#fig:fig1)
для ссылки на него по тексту и размер изображения относительно ширины страницы (width=90%)
Ссылка на изображение (рис. 4.1) может быть оформлена следующим образом
(рис. [-@fig:fig1])




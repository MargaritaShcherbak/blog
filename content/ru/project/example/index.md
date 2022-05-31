---
title: Индивидуальный проект
summary: Теоретическое описание. Добавляем ссылки на научные и библиометрические ресурсы, изменяем информацию о владельцe сайта.
tags:
  - My Project
date: '2022-05-23T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Follow
    url: https://github.com/MargaritaShcherbak
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

## **Цель работы**
Добавить информацию о себе на сайте (биография, аватарка, интресы, образование и два поста).

## **Ход работы**

1. Изменили фотографию владельца сайта на свою. 
(Рис. [-@fig:001])

![Меняем аватарку](image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-05-04%2017-29-44.png){#fig:001 width=70%}

2. - Изменили краткое описание владельца сайта (Biography).
   - Добавили информацию об интересах (Interests).
   - Изменили информацию от образовании (Education). 
   (Рис. [-@fig:002])

Открыли в домашнем каталоге папку work/blog/content/authors/admin/_index.md и внесли изменения, сохранили.

![Редактируем информацию под себя](image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-05-05%2020-58-59.png){#fig:002 width=70%} 

3. Написали 2 поста: 
- по прошедшей неделе
- на тему управления версиями git
 (Рис .[-@fig:003] - Рис .[-@fig:007])

В папке work/blog/content/post мы создали две папки: Last_week для поста по прошедшей неделе и Versioning для поста на тему "Управление версиями. Git". 
Мы копируем файл md из папки getting-started и вставляем этот файл в наши две созданные папки. 
Затем редактируем в кадой папке этот файл в соответсвии теме поста.

![Создание постов](image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-05-04%2017-30-06.png){#fig:003 width=70%}

![Добавили картинку к теме поста о прошедшей неделе](image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-05-04%2017-30-19.png){#fig:004 width=70%}

![Добавили картинку к теме поста об управлениях версиями git](image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-05-04%2017-30-58.png){#fig:005 width=70%}

![Редактирование текста поста о прошедшей неделе](image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-05-05%2021-19-35.png){#fig:006 width=70%}

![Редактирование текста поста об управлениях версиями](image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-05-05%2021-19-58.png){#fig:007 width=70%}

4. После внесённых и сохранённых изменений мы запускаем hugo в каталоге blog, переходим в папку public и вбиваем следующие команды: (Рис .[-@fig:008]).
- git add .
- git commit -am "наш комментарий"
- git push origin main

![Обновляем данные на сайте](image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-05-04%20175117.png){#fig:008 width=70%}

5. Проверяем обновление сайта. (Рис .[-@fig:009] - Рис .[-@fig:0010]).

![Обновлённый сайт](image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-05-04%2017-58-05.png){#fig:009 width=70%}


![Добавились два поста](image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-05-04%2017-58-19.png){#fig:0010 width=70%}

## **Вывод:** 

Таким образом, я добавила информацию о себе на сайте (биографию, аватарку, интресы, образование и два поста).

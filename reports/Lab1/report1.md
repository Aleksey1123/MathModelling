---
## Front matter
title: "Лабораторная работа №1"
subtitle: "Git"
author: "Рытов Алексей Константинович"
lang: ru-RU


## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc-depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# **Цель работы**

– Изучить идеологию и применение средств контроля версий.
– Освоить умения по работе с git.

---

# Выполнение лабораторной работы

1. Натсройка core.autocrlf (рис. 1)</br>

    ![Рис. 1: Натсройка core.autocrlf](images/img_1.png)

---

2. Создание страницы Hello World (рис. 2)

    ![Рис. 2: Создание файла Hello World](images/img_2.png)

Создание репозитория, добавление файла, проверка состояния (рис. 3, 4).

   ![Рис. 3: Работа с репозиторием](images/img_3.png)

   ![Рис. 4: Git status](images/img_4.png)

---
3. Изменение страницы Hello World (рис. 5).

4. Индексация изменений, и их коммит (рис. 5).
![Рис. 5: Git status](images/img_5.png)

Добавление тэгов и их индексация (рис. 6).
    ![Рис. 6: Git status](images/img_6.png)

Коммит индексации. (рис. 7).
    ![Рис. 7: Commit индексации](images/img_7.png)

Просмотр истории (рис. 8).
    ![Рис. 8: История commit'ов](images/img_8.png)

Получаем старые версии (рис. 9).
    ![Рис. 9: Git checkout](images/img_9.png)

Возвращаемся в HEAD (рис. 10).
    ![Рис. 10: Вернулись в HEAD](images/img_10.png)

Создание тэгов и переключение по ним (рис. 11 - 13).

![Рис. 11: Переход по тэгам](images/img_11.png)

![Рис. 12: Переход по тэгам](images/img_12.png)

![Рис. 13: Log](images/img_13.png)

---

5. Отмена локальных изменений (рис. 14).
    ![Рис. 14: Отмена локальных изменений](images/img_14.png)

6. Отмена проиндексированных изменений (перед коммитом) (рис. 15).
![Рис. 15: Отмена проиндексированных изменений](images/img_15.png)

7. Отмена коммитов (рис. 16).
![Рис. 16: Отмена коммитов](images/img_16.png)
Log (рис. 17)
![Рис. 17: Отмена коммитов](images/img_17.png)

8. Удаление коммиттов из ветки (рис. 18 - 19).
![Рис. 18: Пометка коммита перед удалением](images/img_18.png)

![Рис. 19: Сброс commit'ов](images/img_19.png)

9. Удаление тега oops (рис. 20).
![Рис. 20: Удаление тега oops](images/img_20.png)

10. Внесение изменений в коммиты (рис. 21 - 22).
![Рис. 21: Удаление тега oops](images/img_21.png)
![Рис. 21: Log](images/img_22.png)

11. Перемещение файлов (рис. 23).
![Рис. 23: Перемещение файлов](images/img_23.png)
13. Добавление index.html (рис. 24).
![Рис. 24: Добавление index.html](images/img_24.png)

14. .git каталог и базы данных объектов (рис. 25).
![Рис. 25: .git](images/img_25.png)
15. Работа непосредственно с объектами git (рис. 26 - 27).
![Рис. 26: Различные поиски](images/img_26.png)
![Рис. 27: Нахождение изначального commit'a вручную](images/img_27.png)
16. Создание ветки (рис. 28 - 30).
![Рис. 28: Созлание файла стилей](images/img_28.png)
![Рис. 29: Изменение файла стилей](images/img_29.png)
![Рис. 30: Изменение файла стилей](images/img_30.png)
17. Навигация по веткам Создание ветки (рис. 31 - 32).
![Рис. 31: Log -all](images/img_31.png)
![Рис. 32: Переключение по веткам](images/img_32.png)
18. Изменения в ветке master (рис. 33).
    ![Рис. 33: Изменения в ветке master](images/img_33.png)
19. README.md (рис. 34 - 35).
    ![Рис. 34: README.md](images/img_34.png)
    ![Рис. 35: Log --graph](images/img_35.png)
20. Merge (рис. 36).
    ![Рис. 36: Слияние веток](images/img_36.png)
21. Создание конфликта (рис. 37).
    ![Рис. 37: Создание конфликта](images/img_37.png)
22. Разрешение конфликтов (рис. 38).
    ![Рис. 38: Создание конфликта](images/img_38.png)
23. Сброс ветки style (рис. 39 - 40).
    ![Рис. 39: Log](images/img_39.png)
    ![Рис. 40: reset](images/img_40.png)

24. Сброс ветки master (рис. 41).
    ![Рис. 41: reset](images/img_41.png)

25. Rebase (рис. 42).
![Рис. 42: reset](images/img_42.png)

26. Слияние в ветку master (рис. 43).
    ![Рис. 43: Слияние в ветку master](images/img_43.png)
27. Клонирование репозиториев (рис. 44).
![Рис. 44: Клонирование репозиториев](images/img_44.png)
28. Просмотр клонированного репозитория (рис. 45).
    ![Рис. 45: Клонирование репозиториев](images/img_45.png)
29. Origin (рис. 46).
    ![Рис. 46: Remote](images/img_46.png)
30. Удаление ветки (рис. 47).
    ![Рис. 47: Удаление ветки](images/img_47.png)
31. Изменение оригинального репозитория (рис. 48).
![Рис. 48: Изменение оригинального репозитория](images/img_48.png)
32. Слияние извлеченных изменений (рис. 49).
    ![Рис. 49: Изменение оригинального репозитория](images/img_49.png)

33. Добавление ветки наблюдения (рис. 50).
![Рис. 50: Добавление ветки наблюдения](images/img_50.png)
35. Чистый репозиторий (рис. 51).
![Рис. 51: Чистый репозиторий](images/img_51.png)
36. Добавление удаленного репозитория (рис. 52).
![Рис. 52: Добавление удаленного репозитория](images/img_52.png)
37. Отправка изменений (рис. 53).
![Рис. 53: Отправка изменений](images/img_53.png)
38. Извлечение общих изменений (рис. 54).
![Рис. 54: Извлечение общих изменений](images/img_54.png)

---

# Вывод

Мы изучили идеологию и применение средств контроля версий, а также освоили умения по работе с git.</br>

---
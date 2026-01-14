---
layout: page
title: Про курс
description: Загальна інформація.
nav_order: 1
---

# Про курс
{:.no_toc}

## Зміст
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{% assign overview = site.slides | where: "title", "Огляд" | first %}
{{ overview.content }}


Потрiбнi навички
: - Рівень володіння англійською мовою не нижче А2.
- **Математика**: знання та вміння використовувати обчислення, аналітичну геометрію, лінійну алгебру та теорію ймовірностей.
- **Програмування**: написання коду на Python.

Підручники
: 1. Кочура Ю. П., Гордієнко Ю. Г. (2024). [*Нейронні мережі*](https://github.com/dml-book/dml/releases/download/v0.1.10/0.1.10-final.pdf).
1.  Andriy Burkov (2020). [*Machine Learning Engineering*](http://www.mlebook.com/wiki/doku.php?id=start). (MLE)
1. Andriy Burkov (2019). [*The Hundred-Page Machine Learning Book*](http://themlbook.com/wiki/doku.php). (HPML)



## На випадок повітряної тривоги
{% assign siren = site.slides | where: "title", "Повітряна тривога" | first %}
{{ siren.content }}

## Особливостi
{% assign specifics = site.slides | where: "title", "Особливостi" | first %}
{{ specifics.content }}

## Система оцiнювання
{% assign grading = site.slides | where: "title", "Система оцiнювання" | first %}
{{ grading.content }}


## Кодекс честi
{% assign honorcode = site.slides | where: "title", "Кодекс честi" | first %}
{{ honorcode.content }}


## Як успішно завершити курс?
{% assign succeed = site.slides | where: "title", "Як успішно завершити курс?" | first %}
{{ succeed.content }}
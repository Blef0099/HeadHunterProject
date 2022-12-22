
# <center> Демонстрация применения методов преобразования и очистки данных </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Зависимости](#Зависимости)
4. [Установка проекта](#Установка-проекта)
5. [Использование проекта](#Использование-проекта)
6. [Авторы](#Авторы)
7. [Выводы](Использование-проекта)

## Описание проекта

> **Преобразование данных** – это сложный процесс подготовки данных для дальнейшего исследования, который включает в себя сортировку, группировку, составление сводных таблиц и объединение данных.
**Очистка данных** - это процесс обнаружения и удаления (или исправления) поврежденных, ложных или неинформативных записей таблицы или целой базы данных. Процесс состоит из двух этапов: поиск и ликвидация (или редактирование).

Основные этапы подготовки данных:
* Группировка данных
* Сортировка данных
* объединение данных
* Работа с пропущенными значениями.
* Очистка данных от пропусков.
* Удаление признаков и записей, которые не несут полезной информации.

**Цель преобразования и очистки данных** — создать новые важные признаки и избавиться от «мусора», который может помешать моделированию или исказить его результаты. Во многих задачах преобразование и очистка данных — это самая главная часть этапа подготовки данных к построению модели, которая нередко занимает большую часть времени работы над задачей.


**Данный проект** направлен на демонстрацию применения различных методов преобразования и очистки данных на примере датасета из базы данных резюме на HeadHunter.

**О структуре проекта:**
* [plotly](./plotly) - папка с графиками в формате html
* [Project-1. Ноутбук-шаблон.ipynb](./Project-1.Ноутбук-шаблон.ipynb) - jupyter-ноутбук, содержащий основной код проекта 


## Описание данных
В этом проекте используются данные с сайта по поиску вакансий HeadHunter. 

Требования состояли в том, чтобы избавиться от лишних неинформативных признаков, выделив из них наиболее важные признаки для работодателя такие, как: "Пол", "Возраст", "Опыт работы в месяцах", "ЗП в рублях", "Готовность к переездам и к командировкам", "Город", "Тип рабочего графика". 

Исходный датасет представляет собой набор данных с информацией об ожидаемой зарплате соискателей в разных валютах, а также данные о возрасте, опыте работы, городе, желаемом графике работы и т.д.

Для демонстрации техники преобразования и очистки данных мы использовали два датасета с резюме, а также курсами валют. Они содержат информацию об 11 и 7 признаках соответственно. Файлы с данными можно найти [здесь](./dst-3.0_16_1_hh_database.csv) и [здесь](./ExchangeRates.csv)

## Используемые зависимости
* Python (3.9):
    * [numpy (1.20.3)](https://numpy.org)
    * [pandas (1.3.4)](https://pandas.pydata.org)
    * [matplotlib (3.4.3)](https://matplotlib.org)
    * [seaborn (0.11.2)](https://seaborn.pydata.org)
    * [plotly](https://plotly.com/)

## Установка проекта

```
git clone https://github.com/Blef0099/HeadHunterProject
```

## Использование
Вся информация о работе представлена в jupyter-ноутбуке по ссылке https://drive.google.com/drive/folders/164Cr3rOM06z03hOowA0EkYPfGdrb13Lf?usp=share_link

## Авторы

* [Иванов Дмитрий]

## Выводы

Данный проект учит начинающего датасайнтиста правильно подходить к работе с данными. Это работа требует значительного усердия и внимательности обращения с данными, так как именно от этого этапа будет зависить на сколько правильно будут интерпретированы данные на выходе, какие будут сделаны выводы или как будет работать созданная на базе этих данных модель. 
# Проект парсинга pep

[![Python](https://img.shields.io/badge/-Python-464646?style=flat&logo=Python&logoColor=ffffff&color=043A6B)](https://www.python.org/)
[![BeautifulSoup4](https://img.shields.io/badge/-BeautifulSoup4-464646?style=flat&logo=BeautifulSoup4&logoColor=ffffff&color=043A6B)](https://www.crummy.com/software/BeautifulSoup/)
## Описание:

#### Парсер позволяет собирать данные обо все документах PEP, сравнивать статусы на страницах PEP, считать общее количество документов PEP и сохранять результаты в табличном виде в csv-файл..


### Автор проекта:

[Артем Куркин](https://github.com/ArtyKurkin)

### Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/ArtyKurkin/bs4_parser_pep.git
```
```
cd b4_parser_pep
```
Создать и активировать виртуальное окружение:
```
python3 -m venv venv
```
```
source venv/bin/activate 
```
Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```

### Примеры команд:
Создать csv-файл с таблицей из колонок: "Статус" - "Количество" и посчитать общее количество документов:
```
python main.py pep -o file
```
Создать таблицу с помощью prettytable с тремя колонками: "Ссылка на документацию" - "Версия" - "Статус".
```
python main.py latest-versions -o pretty 
```
Вывести ссылки о нововведениях Python в консоль:
```
python main.py whats-new
```
Справка по использованию:
```
python main.py -h
```

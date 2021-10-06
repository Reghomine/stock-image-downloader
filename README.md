## Проект для авто парсинга(скачивания) картинок с сайтов DepositPhotos и ShutterStock
Программу можно развернуть на .ехе файл(зависимости есть в файле requirements.txt) 
Вводные данные: 
1. Кол-во страниц для парсинга 
2. Название файла excel для сохранения расширения и формат фото
3. Поиск(название) рубрики(категории) для поиска

## Установка зависимостей и первый запуск
1.`python -m venv venv`
2.`venv\Scripts\activate`
3.`pip install -r requirements.txt`
4.`python main.py`

## Развернуть на .ехе файл
1.`pyinstaller main.py`

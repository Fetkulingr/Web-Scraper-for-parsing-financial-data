# Web-Scraper-for-parsing-financial-data
![1](https://github.com/Fetkulingr/Web-Scraper-for-parsing-financial-data/assets/103204349/bf5fd339-07f5-4b10-9cee-d9588faae5ee)

# Описание программы:
Web Scraper для парсинга финансовых данных - это инструмент, который позволяет автоматически собирать и сохранять информацию о финансовых данных со страницы сайта. Программа использует Selenium WebDriver для взаимодействия с веб-страницей и извлечения данных.
# Основные функции программы:
1. Парсинг данных: Программа извлекает финансовые данные с указанной веб-страницы и сохраняет их в формате CSV.
2. Автоматическая загрузка данных: Программа автоматически открывает страницу с данными, ожидает загрузку таблицы и извлекает ее содержимое.
3. Удобное сохранение данных: Каждый раз парсинга создает новый файл CSV, включающий дату, время и данные.
# Инструкция по использованию программы:

1. Установите необходимые зависимости, включая Selenium WebDriver.
2. Укажите путь к драйверу Chrome в переменной chromedriver_path.
3. Запустите программу и она автоматически начнет парсить данные с указанной веб-страницы.
4. Для каждого парсинга будет создан новый файл CSV, содержащий дату, время и данные.
5. Измените начальную и конечную даты в соответствии с вашими потребностями, указав их в переменных start_date и end_date.
6. Проверьте, является ли текущая дата рабочим днем, используя функцию is_weekday, и измените ее логику при необходимости.
7. Запустите программу и она будет автоматически парсить данные каждый рабочий день в заданном диапазоне дат.
8. Проверьте созданные файлы CSV для полученных данных.

Обратите внимание, что программа предоставляется "как есть" и требует дополнительной настройки и обработки ошибок в зависимости от ваших потребностей.

# Тестовое задание для вакансии php-разработчик

Имеются компании (company), которые могут иметь несколько своих тв-тарифов (tariff). К каждой компании могут подключаются клиенты (customer) на выбранные тарифы (можно несколько). Компании могут так же временно отключать клиентов.

1. Написать структуру таблиц MySQL для хранения этих данных.

2. Написать SQL-запросы для получения:
- Количество всех клиентов, подписанных хоть на один тариф (по компаниям)
- Количество неактивных клиентов, подписанных на тарифы (по компаниям)
- Список тарифов и количество активных клиентов подписанных на эти тарифы (по компаниям)
- Список активных клиентов и тарифы, на которые они подписаны

3. Написать консольный php-скрипт для формирования отчетов компаний в разных форматах. В результате работы скрипта должен быть получен набор файлов с названием <company-name>-<report-date>.<file_type>

Внутри каждого файла:
• будет название компании, дата формирования отчета
• результаты запросов из п. 2 

4. Форматы файлов:
1. XML
2. CSV
3. JSON
4. Excel

При написании скрипта можно использовать любой фреймворк.

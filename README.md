# Сравниваем вакансии программистов

Проект предназначен для анализа рынка вакансий программистов на основе данных с сайтов [HeadHunter.ru](https://hh.ru/) и [SuperJob.ru](https://www.superjob.ru//). Программа выводит таблицу со статистикой по языкам программирования, основные метрики — количество вакансий и средняя зарплата.

### Как установить

1. Python3 должен быть уже установлен.  
2. Затем используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```
3. Рекомендуется использовать [virtualenv/venv](https://docs.python.org/3/library/venv.html) для изоляции проекта.
4. Для работы с Api SuperJob требуется `Secret key`, чтобы получить его, зарегистрируйте приложение на [api.superjob](https://api.superjob.ru/). Полученный ключ следует положить в файл `.env` под именем `SUPERJOB_SECRET_KEY`.
5. Запустите файл `salary_analyzer.py`.   

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).
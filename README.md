# vstup.edbo.gov.ua-parser
### Парсер сайту https://vstup.edbo.gov.ua/

Збирає та виводить у консоль інформацію про заяви, що подали абітуруєнти на вступ, за вказаними параметрами:
- потрібні факультети;
- сортування заяв за балом;
- за статусом;
- за пріоритетами.


Мені було впадло робити якийсь нормальний інтерфейс, тому тут все захардкоджено.
Змінюйте окремі частини коду під свої потреби і запускайте проєкт з-під __IDE__ _(PyCharm, VS 2019, VS Code тощо)_


Змінити перелік факультетів на пошук:    ```main.py -> faculties```

Змінити фільтри пошуку по таблиці заяв:  ```data_table.py -> def apply_show_info_filters(row)```


Щодо "фільтрів пошуку по таблиці заяв" - за замовчуванням відображаються абітурієнти, що є:
- із __*балом*__ не менше 194.0;
- зі __*статусом*__ "допущено", "зареєстровано" або "заява надійшла з сайту";
- мають __*пріоритети*__ 1 або 2.

Перелік можливих __*статусів*__: ```app_status.py```


![](screens/3.png)

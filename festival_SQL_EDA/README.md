# Данные:
### Таблица airports:
- airport_code — трёхбуквенный код аэропорта
- airport_name — название аэропорта
- city — город
- timezone — временная зона
### Таблица aircrafts:
- aircraft_code — код модели самолёта
- model — модель самолёта
- range — дальность полёта
### Таблица tickets:
- ticket_no — уникальный номер билета
- passenger_id — персональный идентификатор пассажира
- passenger_name — имя и фамилия пассажира
### Таблица flights:
- flight_id — уникальный идентификатор рейса
- departure_airport — аэропорт вылета
- departure_time — дата и время вылета
- arrival_airport — аэропорт прилёта
- arrival_time — дата и время прилёта
- aircraft_code — id самолёта
### Таблица ticket_flights:
- ticket_no — номер билета
- flight_id — идентификатор рейса
### Таблица festivals:
- festival_id — уникальный номер фестиваля
- festival_date — дата проведения фестиваля
- festival_city — город проведения фестиваля
- festival_name — название фестиваля

# Задача:
Менеджер авиаперевозчика готовит исследование. Он хочет выявить связь между числом полётов, типом самолётов и календарём музыкальных фестивалей.

# Используемые библиотеки
- scipy
- pyspark
  - sql.SparkSession
- matplotli
- seaborn

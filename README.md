# TestHTTP
## Запуск тестов
```
python3 -m pytest test.py
```
## Результат выполнения
## Обнаруженные баги
В результате выполнения тестов и с помощью ручного тестирования были обнаружены следующие баги
+ Символ 'i' воспринимается сервером как символ '1'
  Пример запроса
  ```
  {"string": "2i3"}


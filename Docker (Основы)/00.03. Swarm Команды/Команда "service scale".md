#flashcards
***
Изменяет количество реплик, то есть копий ([[Задача (Task) в Swarm]]) одного [[Сервис в Swarm]].
***Синтаксис***:
>***docker service scale <сервис>=<реплика> ...***
- Можно задавать несколько настроек подряд в одну строку.
***
***Примеры***:
1. docker service scale web=5
2. docker service scale web=5 api=3 worker=10
3. docker service scale web=0 (остановить все реплики)
<!--SR:!2025-11-18,4,230-->
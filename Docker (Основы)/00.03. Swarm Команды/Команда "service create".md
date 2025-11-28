#flashcards
***
Создает новый [[Сервис в Swarm]].
Синтаксис:
>***docker service create <опции> <образ> <команда> <аргументы>***
- <опции> = флаги.
***
***Флаги***:
1. --name <имя> - Имя сервиса.
2. --replicas < N> - Количество реплик (если сервис реплицированный).
3. --mode < replicated|global> - Тип сервиса. По умолчанию replicated.
4. --mount type=< volume|bind>,source=< source>,target=< target> - Монтирование [[Том Docker]] или просто [[Bind Mount (Монтирование каталогов с хоста)]]
5. --network < network> - Подключение к [[Сеть Docker]].
<!--SR:!2025-12-18,21,230-->
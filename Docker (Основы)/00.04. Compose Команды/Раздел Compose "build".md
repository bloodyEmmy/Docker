#flashcards
***
Используется, если нам необходимо самостоятельно собрать [[Образ контейнера (Docker Image)]] из написанного ранее [[Dockerfile]].
***Пример***:
>services:
>	app:
>		build:
>			context: .
>			dockerfile: Dockerfile
<!--SR:!2025-11-08,7,250-->
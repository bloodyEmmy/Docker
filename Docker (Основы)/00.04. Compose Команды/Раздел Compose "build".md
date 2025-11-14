#flashcards
***
Используется, если нам необходимо самостоятельно собрать [[Образ контейнера (Docker Image)]] из написанного ранее [[Dockerfile]].
***Пример***:
>services:
>	app:
>		build:
>			context: .
>			dockerfile: Dockerfile
<!--SR:!2025-12-01,17,250-->
# ТЗ

На основе API [https://rickandmortyapi.com/](https://rickandmortyapi.com/),
реализовать React приложение, lazy-список героев из мультсериала
(lazy-список - список, в котором элементы подгружаются с бекенда частями,
т.е. когда скролл доходит до конца страницы - получаем следующую часть списка и т.д. пока у бекенда еще есть для нас данные).

По нажатию на персонажа должен осуществляться переход на отдельную страницу с подробной информацией о нём.
Для управлением стейта использовать Redux, для асинхронных запросов Redux-Saga.
Для стилей использовать SCSS или StyledComponents.

https://rickandmortyapi.com/api/character

# Решение:

1- Для управлением стейта, асинхронных запросов был использован (mobx,mobx-state-tree).\
2- Для стилей использован StyledComponents.

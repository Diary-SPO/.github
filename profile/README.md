# Дневник СПО

Дневник СПО — обёртка над дневником Сетевого города для СПО (как минимум API совпадает с Томской областью)

## Frontend
Клиентская часть написана на Preact / TS / VKUI / VK mini-apps-router с использованием VK Bridge для взаимодействия с юзером внутри VK 

Сервис также работает за пределами VK.

## Backend

Сервер по сути является прокси, потому что из клиентской части нельзя делать запросы на бэк сетевого города.

Написан на Elysia / TS на основе новой JS runtime платформы Bun. Также есть сервер на Go, который более не используется

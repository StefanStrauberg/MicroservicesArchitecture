# Microservices Architecture on .NET

## Описание проекта

Этот проект демонстрирует применение принципов микросервисной архитектуры в .NET с использованием лучших практик и современных технологий.
Он разработан для изучения и реализации концепций, освещённых в курсе [Microservices Architecture and Implementation on .NET](https://www.udemy.com/course/microservices-architecture-and-implementation-on-dotnet/).

## Цели проекта

- Понять и углубить принципы микросервисной архитектуры.
- Построить scalable и maintainable систему на основе микросервисов.
- Реализовать взаимодействие микросервисов с помощью REST API, gRPC, RabbitMQ.
- Использовать Docker, Docker-Compose для управления и развертывания микросервисов.
- Использовать Redis для кеширования, оптимизации и ускорения.
- Использовать Yarp API Gateway в качестве proxy-сервера.

## Основные технологии

- **C# и .NET**: Основной язык и фреймворк для разработки.
- **Entity Framework Core**: ORM для работы с базой данных.
- **Docker и Docker-Compose**: Инструменты для контейнеризации и оркестрации.
- **RabbitMQ, gRPC**: Мессенджинг между микросервисами.
- **Swagger**: Документация API.

## Структура проекта

- **API Gateway**: Управление входящими запросами и маршрутизация.
- **Identity Server**: Управление пользователями и авторизацией.
- **Catalog API**: Работа с каталогом продуктов.
- **Basket API**: Обработка заказов клиентов.
- **Discount API**: Работа с купонами и скидками.

## Установка и запуск проекта

1. Установите [Docker](https://www.docker.com/get-started) и [Kubernetes](https://kubernetes.io/).
2. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/yourusername/microservices-architecture.git
   cd microservices-architecture
   ```

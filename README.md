# 👨‍💻 Александр Юрлов — Python Backend разработчик

Python backend разработчик с 1.5 годами коммерческого опыта. Проектирую RESTful API и сервисы интеграции с внешними системами. Реализовывал аутентификацию и авторизацию через OAuth 2.0 и JWT. Работаю с FastAPI и Sanic, PostgreSQL, MongoDB, Redis. Уделяю внимание безопасности, тестированию и качеству кода.

---

## ⚙️ Стек и технологии

**Языки и фреймворки**

![Python](https://img.shields.io/badge/-Python-000?&logo=python)
![FastAPI](https://img.shields.io/badge/-FastAPI-000?&logo=fastapi)
![Sanic](https://img.shields.io/badge/-Sanic-000?&logo=python)
![Pydantic](https://img.shields.io/badge/-Pydantic-000?&logo=pydantic)

**Базы данных**

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-000?&logo=postgresql)
![MSSQL](https://img.shields.io/badge/-MSSQL-000?&logo=microsoftsqlserver)
![MongoDB](https://img.shields.io/badge/-MongoDB-000?&logo=mongodb)
![Redis](https://img.shields.io/badge/-Redis-000?&logo=redis)

**Инструменты и DevOps**

![Docker](https://img.shields.io/badge/-Docker-000?&logo=docker)
![GitLab CI](https://img.shields.io/badge/-GitLab%20CI-000?&logo=gitlab)
![Git](https://img.shields.io/badge/-Git-000?&logo=git)
![Poetry](https://img.shields.io/badge/-Poetry-000?&logo=poetry)

**Качество кода**

![pytest](https://img.shields.io/badge/-pytest-000?&logo=pytest)
![Ruff](https://img.shields.io/badge/-Ruff-000?&logo=ruff)
![MyPy](https://img.shields.io/badge/-MyPy-000?&logo=python)

---

## 📄 Опыт работы

**Python Backend разработчик — АО "ТРИЦ"**
[www.itpc.ru](https://www.itpc.ru) — Тюмень
*Июнь 2024 — Ноябрь 2025 (1.5 года)*

Разработка микросервисов для платформы ЖКХ-услуг: личные кабинеты, биллинг, CRM-интеграции.

### API и интеграции с внешними системами

- 🔐 **Сервис авторизации OAuth 2.0** — RESTful API для аутентификации через VK и Yandex. PKCE, JWT-токены, state-параметры для защиты от CSRF, управление сессиями через Redis. Привязка/отвязка провайдеров, автоматическое слияние дублирующихся аккаунтов
- 🔌 **Маршрутизаторы CRM** — два сервиса интеграции внешних платформ: Freshchat ↔ Chatwoot и VK ↔ Chatwoot. Приём webhook-ов, асинхронная обработка через Actor-модель, надёжная доставка с retry, шифрование данных
- 👤 **Сервис управления пользователями** — CRUD API для аккаунтов и личных счетов, токенная аутентификация, привязка пользователей к организациям, кэширование через Redis
- ✉️ **Валидация email**: DNS-проверка MX-записей, автоисправление опечаток через нечёткий поиск (rapidfuzz)

### Базы данных и миграции

- 💳 **Интеграция с биллингом** — SQL-запросы к PostgreSQL и MSSQL для синхронизации клиентов, счетов и показаний приборов учёта. ORM-моделирование через aiomotorengine (MongoDB), прямые SQL-запросы для реляционных БД
- 🔄 **Инструмент миграций** — Docker-контейнер для выполнения SQL-миграций PostgreSQL и MSSQL с retry-логикой, интеграцией в GitLab CI

### Безопасность и качество кода

- Аутентификация и авторизация: JWT, OAuth 2.0 с PKCE, токенная защита эндпоинтов
- Валидация входящих данных через Pydantic-схемы, шифрование чувствительных данных (cryptography)
- Unit и интеграционные тесты (pytest), покрытие ~75%
- CI/CD: GitLab CI — линтинг (Ruff), типизация (MyPy), тесты, Docker-деплой

---

## 🎓 Образование

**Университет ИТМО** — Нейротехнологии и программирование (2022–2026)

---

## 💡 Дополнительно

- Асинхронное программирование: Actor-модель, Redis RPC/Pub-Sub для межсервисного взаимодействия
- Процессы: Scrum, GitFlow, YouTrack
- ML/CV: видеоаналитика — детекция и трекинг объектов (YOLOv8, PyTorch, OpenCV)

---

## 📫 Связь

[![Telegram](https://img.shields.io/badge/-@JohnSliver-000?&logo=telegram)](https://t.me/JohnSliver)
[![Email](https://img.shields.io/badge/-sasha.yur@mail.ru-000?&logo=mail.ru)](mailto:sasha.yur@mail.ru)

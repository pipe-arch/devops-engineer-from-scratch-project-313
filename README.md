# Деплой приложения на PaaS (Devops)

[![hexlet-check](https://github.com/pipe-arch/devops-engineer-from-scratch-project-313/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/pipe-arch/devops-engineer-from-scratch-project-313/actions)

Создайте и задеплойте веб-приложение, подключите базу данных и настройте мониторинг ошибок

Учебный проект Хекслета: https://ru.hexlet.io/programs/devops-engineer-from-scratch


## Стек

- Python 3.12
- Flask
- uv

## Установка

```bash
git clone https://github.com/pipe-arch/devops-engineer-from-scratch-project-313.git
cd devops-engineer-from-scratch-project-313
uv sync
```

## Использование

Запуск приложения на порту 8080:

```bash
make run
```

В другом терминале проверяем, что приложение отвечает:

```bash
curl localhost:8080/ping
# pong
```

Остановка - `Ctrl+C`. Без `make` приложение запускается так: `uv run python main.py`.

---

<details>
<summary>Автоматические тесты Хекслета</summary>

Тесты запускаются на каждый коммит. За запуск отвечает файл `.github/workflows/hexlet-check.yml` — не удаляйте и не переименовывайте ни его, ни репозиторий.

</details>

## О Хекслете

[Хекслет](https://ru.hexlet.io/) — школа программирования: авторские программы обучения с практикой, поддержкой наставников и реальными проектами, которые остаются в резюме. Этот репозиторий — один из таких проектов.

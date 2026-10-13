# Well Monitor (расширенный трек)

## Назначение
Учебный проект мониторинга нефтяной скважины с настроенным
рабочим местом разработчика.

## Требования
- Python 3.11+
- Visual Studio Code с расширениями Python и Python Debugger
- Git
- 
## Создание окружения
    python -m venv .venv
    .\.venv\Scripts\Activate.ps1

## Запуск из терминала
    $env:PYTHONPATH="src"
    python -m well_monitor.main

## Запуск через VS Code
Нажмите F5 (конфигурация в .vscode/launch.json).

## Отладка
Поставьте точку останова в main.py и нажмите F5.

## Структура проекта
    src/well_monitor/ — исходный код
    .vscode/ — настройки VS Code
    pyproject.toml — метаданные проекта
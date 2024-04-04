# Отчет Allure

Этот репозиторий содержит пример теста Selenium с использованием библиотеки Allure для генерации отчетов о выполнении тестов.

## Установка зависимостей

Для запуска теста вам потребуются следующие зависимости:

- Python
- pytest
- selenium
- allure-pytest

Вы можете установить их с помощью следующей команды:

```bash
pip install pytest selenium allure-pytest
```
```bash
pip install selenium
```
```bash
pip install pytest
```

Запуск

```bash
pytest -s --alluredir allure-results mazila.py
```

## Скриншоты
|Главная страница отчета| Подробности |
|----------------------|------------------------|
| ![Главная страница отчета](![image](https://github.com/VsevolodYatsuk/allure-report/assets/130091517/b9e8a3c1-e795-487f-80ef-33751ad6cd8d)
) | ![Подробности](![image](https://github.com/VsevolodYatsuk/allure-report/assets/130091517/01f899f8-8b73-4fec-933d-d4bef2d4e5d1)
) |

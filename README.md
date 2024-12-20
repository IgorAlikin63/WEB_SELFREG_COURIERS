# WEB_SELFREG_COURIERS

# Запустите тесты
pytest tests/test_main_page.py

pip freeze > requirements.txt

pip install -U pytest

python -m pip install selenium

pip install allure-pytest

Генерация отчета Allure:

pytest test_main_page.py --alluredir=allure_results

allure serve allure_results
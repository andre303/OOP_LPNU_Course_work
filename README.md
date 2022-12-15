Для встановлення і запуску проекту потрібно виконати наступні кроки:
1.	Встановити з офіційного сайту мову програмування Python
2.	Скачати архів з проектом або клонувати репозиторій з гіт хабу
3.	Відкрити консоль у головній директорії проекту (там де знаходиться файл manage.py)
4.	Встановити всі необхідні бібліотеки за допомогою команди 
pip install -r requirements.txt
5.	Зібрати всі статичні  файли за допомогою команди
python manage.py collectstatic
6.	Виконати міграцію бази даних за допомогою команди
python manage.py migrate
7.	Для запуску проекту ввести команду
python manage.py runserver та зайти у браузері за посиланням http://127.0.0.1:8000/
Додатково для доступу до адмін панелі можна ввести команду 
python manage.py createsuperuser

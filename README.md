# mle-template-case-sprint2

Добро пожаловать в репозиторий-шаблон Практикума для проекта 2 спринта. Ваша цель — улучшить ключевые метрики модели для предсказания стоимости квартир Яндекс Недвижимости.

Полное описание проекта хранится в уроке «Проект. Улучшение baseline-модели» на учебной платформе.

Здесь укажите имя вашего бакета:
s3-student-mle-20240325-31df1ce58e

Последовательность шагов:

git clone <ссылка-на-ваш-репозиторий>
cd <название-вашего-проекта>
sudo apt-get update
sudo apt-get install python3.10-venv
python3.10 -m venv .venv_project_name
source .venv_project_name/bin/activate 
pip install -r requirements.txt 

Этап 1: Разворачивание MLflow с отдельным Tracking Server, реляционной базой данных и хранилищем для артефактов и регистрация модели MLflow 
1. В .env файл указываем соответсвующие значения для переменных окружения;
2. export $(cat .env | xargs) ;
3. sh run_mlflow_server.sh ;

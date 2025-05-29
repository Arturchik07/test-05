git clone ,,,cd blog_api
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser  
python manage.py runserver


docer 

git clone <>
cd blog_api
docker-compose up --build
docker-compose exec app python manage.py migrate
docker-compose exec app python manage.py createsuperuser





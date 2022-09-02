FROM python


RUN pip install -r requirements.txt
RUN . env/bin/activate

RUN python manage.py makemigrations
RUN python manage.py migrate
RUN python manage.py runserver


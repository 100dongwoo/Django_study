# Django_study
Django 첫 공부 파일 


## Django init
- django-admin startproject mysite

## Django run 
- python manage.py runserver


## Change port 
- python manage.py runserver 8080


## Create app
- python manage.py startapp polls

# 가상서버 만들기

```
# 프로젝트 내의 가상환경을 만들어줍니다.
python -m venv venv

# 가상환경을 활성화해줍니다.
. venv/bin/activate         - mac
venv\Scripts\activate.bat   - window

# 데이터베이스에 변경이 있으므로 이를 반영해주는 migrate 명령어를 입력합니다.
python manage.py migrate

# 웹 서버를 실행합니다.
python manage.py runserver
```


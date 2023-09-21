# 개인사업자 양도양수 경매 사이트 어플리케이션 프로젝트 계획

## 제안서

이 프로젝트는 개인사업자 경매 사이트 어플리케이션을 개발하는 것을 목표로 합니다. 이 어플리케이션은 개인사업자 판매자와 구매자 간의 경매를 통해 편하게 사업을 할 수 있는 플랫폼을 제공합니다. 판매자는 어플에서 경매를 시작하고, 구매자는 해당 경매에 입찰하여 정확한 정보로 간단히 가게를 인수 받을 수 있습니다.

![image](https://github.com/Kangai1/kangai1/assets/144196895/e4e7bd15-62b8-4edc-891b-b1fa6b8eeec3)


## 프로그램

프로젝트를 개발하기 위해 다음과 같은 주요 프로그램을 사용할 예정입니다:

- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/): 웹 애플리케이션 개발 프레임워크
- [Django REST framework](https://www.django-rest-framework.org/): RESTful API 개발 도구
- [React](https://reactjs.org/): 사용자 인터페이스 개발을 위한 JavaScript 라이브러리
- [PostgreSQL](https://www.postgresql.org/): 데이터베이스 관리 시스템

## 설치

프로젝트를 로컬 환경에서 실행하려면 다음 단계를 따르십시오 (실제로 이 명령을 실행하지 마세요):

1. Python 및 pip를 설치하세요.


$ sudo apt update
$ sudo apt install python3 python3-pip

2. 가상 환경을 생성하고 활성화하세요.

$ python3 -m venv venv
$ source venv/bin/activate

3. Django 및 관련 패키지를 설치하세요.

(venv) $ pip install django djangorestframework

4. Clone the project and install dependencies.


(venv) $ git clone https://github.com/yourusername/restaurant-auction-app.git
(venv) $ cd restaurant-auction-app
(venv) $ pip install -r requirements.txt

5. 데이터베이스 마이그레이션을 실행하세요.

(venv) $ python manage.py migrate

6. 개발 서버를 시작하세요.
   
(venv) $ python manage.py runserver





## About

- drf-pyotp is `DRF` extension of [PyOTP](https://github.com/pyotp/pyotp) and forker from [drf-pyotp](https://github.com/inforian/drf-pyotp)
- It hadles OTP generate and verification based on time and count based.

## Prerequisites :

#### Environment Variables : 

 - DATABASE_NAME_PYOTP
 - DATABASE_USER
 - DATABASE_PASSWORD
 - DATABASE_HOST
 - DATABASE_PORT
 - SECRET_KEY
 
## Installation :

1 ) Clone this repo

2 ) Setup virtual environment
```
cd <path-to-repo>/drf-pyotp/

virtualenv -p /usr/bin/python3 env

```

3 ) Activate Virtual environment
```
source env/bin/activate
```
4 ) Install requirements

```
pip install -r requirements.txt

```
5 ) Prerequisites
 - Makes sure above `Prerequisites` are defined and fulfilled.

6 ) Run Server 
```
python manage.py runserver
```

## API Reference : 

- API documentation is hosted on [Swagger hub](https://swaggerhub.com/apis/verisadmin/Rest-PyOTP/0.1) 
and is public.

## Tests : 

- Run tests using 
```
make test
```
 
 
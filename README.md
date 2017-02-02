#Django

간단한 설명:
'''
manage.py : django 프로젝트 관리
settings.py : 장고에 관한 각종 설정들
urls.py : 홈페이지 주소를 장고와 연결 해 주는 역할
wsgi.py : 장고 실행 서버 관련 설정
'''
  

1. 가상환경 설정(Windows)
윈도우즈에서 가상환경을 만들기 위해서는 Python으로 Tools\scripts\pyvenv.py 파일을 아래와 같이 실행한다. 즉, Python35 폴더에 Python 3.5가 설치되어 있다고 가정하고, 툴 스크립트인 pyvenv.py를 가상환경 디렉토리(C:\PyEnv\venv1)와 함께 실행한 것이다.
윈도우즈에서 가상환경을 활성화(activate)하기 위해서는 다음과 같이 가상환경 디렉토리 밑의 Scripts 서브 폴더에 있는 activate.bat 를 실행하면 된다.

'''
C:\Python35> python Tools\scripts\pyvenv.py C:\PyEnv\venv1
C:\PyEnv\venv1> Scripts\activate.bat
'''



django 관리자 등록 :

'''
manage.py createsuperuser
'''
위의 명령어를 입력하면 Username, Email, Password를 입력 하게 된다.

  

django 새로운 프로젝트 생성 :
'''
manage.py startapp newproject
'''
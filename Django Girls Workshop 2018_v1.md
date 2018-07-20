### 2018.07.20 ~ 2017.07.21 Django Girls Workshop



#### 2018.07.20 1st Day : Setting

- Django Girls Seoul 소개

  - 워크샵 소개, 규칙 안내

  - 튜토리얼 소개 : https://tutorial.djangogirls.org/ko/

    

- Python 설치하기 : 3.6.x 버전

  - <https://www.python.org/downloads/windows/>  

  - 윈도우 32비트 / 64비트 확인 후 다운로드

  - Add Python 3.6 to PATH 선택

    

- Virtualenv 환경 (Virtual Environment) 설정

  ~~~
  $ mkdir djangogirls
  $ cd djangogirls
  
  C:\Users\Name\djangogirls> C:\Python36\python -m -venv myvenv
  # Name : 윈도우 사용자 이름
  # C:\Python36\python : 파이썬 3.6 설치한 경로
  
  C:\Users\Name\djangogirls> myvenv\Scripts\activate
  # Name : 윈도우 사용자 이름
  ~~~

  ~~~
  # 상기 Activate 명령이 실행되지 않는 경우 다음과 같이 설정
  C:\Windows\system32> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned
  -> A 옵션 선택
  ~~~

  

- Django (장고) 설치하기

  ~~~
  $ python3 -m pip install --upgrade pip  # pip의 버전 확인
  $ pip install django~=1.11.0  # django 설치
  ~~~

  

- 코드 에디터 설치하기 : Sublime Text 3, Gedit, Atom 중 선택

  

- Git 설치하기 

  - 기본 설정대로 설치
  - 단, PATH 환경 설정은 '윈도우 커맨드라인에서 Git과 유닉스 도구를 사용' 선택

  

- [GitHub](https://github.com/), [PythonAnywhere](https://www.pythonanywhere.com) 계정 만들기

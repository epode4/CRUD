# CRUD
> `< >` 에는 생성하고 싶은 프로젝트 이름 작성


1. 프로젝트 폴더 생성

2. 프로젝트 폴더로 이동/ vscode 실행
    -`.gitignore`, `README.md` 생성
3. django 프로젝트 생성
```bash
django-admin startproject <pjtname> .
```

4. 가상환경 설정
```bash
python -m venv venvs
```

5. 가상환경 활성화 / 비활성화
```bash
source venv/Scripts/activate
diactivate
```

6. 가상환경에 django 설치
```bash
pip install django
```

7. 서버 실행 확인
```bash
python manage.py runserver
```

8. 앱 생성
```bash
django-admin startapp <appname>
```
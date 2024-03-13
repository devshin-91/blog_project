#tube-clone-project
유튜브 클론 프로젝트

## 1. 개요
- 장고 프레임워크에서 유튜브 기능을 구현하여 장고를 학습

## 2. 프로필
<table>
    <tr>
        <th>신찬수</th>
    </tr>
        <td><img src="profile.jpg"  alt="프로필 사진"></td>
</table>

## 3. 개발환경
- 운영체제
    - Windows 10
- 에디터
    - VS Code
- 프레임워크
    - Django

## 4. Django 및 라이브러리 버전
```
asgiref==3.7.2
Django==5.0.2
pillow==10.2.0
sqlparse==0.4.4
tzdata==2024.1
```

## 5. 사용방법

0. (옵션) 기존 내용을 지우고 사용하고자 한다면
- db.sqlite3 파일 삭제
- .\media\blog\files 하위 폴더 삭제
- .\media\images 하위 폴더 삭제

1. 가상환경 생성 및 접속
```cmd
> python -m venv venv
> .\venv\Scripts\activate
```
2. 필수 라이브러리 설치
```cmd
> pip install -r requirements.txt
```
3. DB 초기화
```cmd
> python manage.py makemigrations
> python manage.py migrate
```
4. admin 계정 새로 생성 (기존 admin 계정: admin, 비밀번호: Admin12#$)
```cmd
> python manage.py createsuperuser
```
5. 장고 서버 실행
```
> python manage.py runserver
```

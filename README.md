# Git 명령어

## Git 로컬 컴퓨터에 사용자 등록하기

- git config --global user.name "unyak"
- git config --global user.email "0106un@naver.com"

## Git 시작하기

- git init
- git add . // .뒤에 파일명을 적는대 .하면 전부라는 뜻임
- git commit -m "최초 커밋"

## Github 업로드하기

- git remote add origin 주소
- git push origin master

## 다시 업로드 법
- 소스코드 변경
- git add .
- git commit -m "변경내용적고"
- git push origin master
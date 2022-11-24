# ■ 깃허브 명령어
## 깃 정보확인
git status

## 내용 되돌리기
git checkout -- "파일명.확장자"

## 수정한 거 업로드하는 법.
git add .  
git commit -m "파일에 표시할 주석(날짜, 버전 등)"  
git push

# ■ 파일 연동 및 업로드 순서
## 초기설정(이미 한 PC명 생략 가능)
git config --global user.name 유저이름  
git config --global user.email 유저이메일  

## 파일 준비
git init // #.git 파일 생성  
git add . // 선택한 프로젝트 폴더 내의 모든 파일 관리  
git commit -m "설명" // 커밋  

## 업로드
git remote add origin 레파지토리주소  
git push -u origin master  

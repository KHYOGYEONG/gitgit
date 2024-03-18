# **제목- 유비온**

일자 _ 2024_03_18 11:05

#### **프로젝트 생성**

- 프로젝트 폴더 생성 후 VS code에서 폴더 열기
- git에서 관리하지 않을 파일 설정 : .gitignore 파일 생성 후 파일에 관리하지 않을 파일 저장
  (https://git-scm.com/docs/gitignore 참조)

```cmd
## 터미널 열어서 폴더 경로에서 git 연동 
git init

## git 현재 상태 확인
git status


## .gitignore 파일 설정
# 모든 file.c
file.c

# 최상위 폴더의 file.c
/file.c

# 모든 .c 확장자 파일
*.c
```

------

### **Git에 파일 반영하기**

```cmd
## 버전에 파일 담기
git add filename.py

# 모든 파일 담기
git add .

# git add 취소하기
git rm --cached <file>

## 버전으로 묶어주기
# vi 입력모드로 진입
git commit

# 커밋 메세지 한 번에 작성
git commit -m "comment"

# 커밋 이력 확인
git log
```


# Markdown
- backtick 사용해서 코드 블록 만들기 
- 이미지: ! + url 통해 이미지 사용 가능
- > 인용문 사용
> 이렇게 인용문을 사용합니다.
# 1) Initiating git

git init #initiate git

git commit -m ‘메시지’ #메세지라는 이름으로 커밋

touch a.txt  #make a new text file

git stautus #상태 확인

git add . #모든 파일을 add

git log # 커밋 히스토리 조회


# 2) GUI (Graphic User Interface)
- 그래픽 기반 인터페이스 
- 명령 후 실행을 하며 결과를 읽게 됨 

# 3) CLI 명령어
- 명령 기반 인터페이스

- pwd : print working directory

- ls : list(파일 목록)

- touch : 파일 만들기

- rm : 파일 삭제

- mkdir: make directory

- cd: change directory 하위 폴더에 들어가기

- cd ..: 상위 폴더로 올라가기

- cd 폴더명 : 해당 폴더로 들어가기


**중요
1. 작업을 하고
2. 변경된 파일을 모아(add)
3. 버전으로 남긴다 (commit)


06/08
# How to create pull request

1. fork: pull request 하는 git repository 에서 fork 눌러서 저장소 생성 
2. clone: 내 repository에서 url 복사 후 원격 저장소 지정하기 
3. commit: 수정한 내용 commit 하기
4. remote : 원본 저장소와 연결
5. pull request: github web 에 들어가서 pull request 전달하기 

# git 저장소 만들기 
  > $ cd /Users/user/my_project
  > git init

 $ git add *.c
 $ git add LICENSE
 $ git commit -m 'initial project version'
 
 # git 버전 관리 
  $ git status #  
  $ git log #커밋 기록 조회 (현재 저장된 커밋을 조회)
      - git log -1
      - git log --online
      
 # git push?
 -  로컬 -> 원격 저장소로 보내는 것
 -  
 # git pull?
 - 원격 저장소 버전 -> 로컬 저장소

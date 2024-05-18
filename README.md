# 1. git init:

 ### 1.1 현재 디렉터리에 새로운 Git 저장소를 초기화합니다. 이 명령어를 실행하면 .git 하위 디렉터리가 생성되고, 여기에 모든 메타데이터와 저장소 이력이 저장됩니다.

# 2. git add README.md: 

 ### 2.1 README.md 파일을 스테이징 영역에 추가합니다. 스테이징은 해당 파일이 다음 커밋에 포함되도록 표시하는 것을 의미합니다.

# 3. git commit -m "first commit":

 ### 3.1 스테이징된 파일(README.md)을 커밋합니다. -m 옵션은 커밋 메시지를 명령줄에서 바로 입력할 수 있게 해주며, 여기서는 "first commit"이라는 메시지를 사용했습니다.

# 4. git branch -M main: 

 ### 4.1 현재 브랜치를 main으로 이름을 변경합니다. -M 옵션은 강제로 이름을 변경하고 브랜치를 새로운 이름으로 이동시킵니다.

# 5. git remote add origin https://github.com/Hamseungjin/delte.git: 
 
### 5.1 git remote add [별칭] [원격 저장소 URL]

### 5.2 origin이라는 이름의 원격 저장소를 추가합니다. 지정된 URL(https://github.com/Hamseungjin/delte.git)은 GitHub에 있는 원격 저장소의 위치입니다. 

# 6. git push -u origin main: 
 
### 6.1 git push -u [원격 저장소 이름] [로컬 저장소의 브랜치 이름]

### 6.2 로컬 main 브랜치를 원격 저장소(origin)에 푸시합니다. -u 옵션은 origin main을 main 브랜치의 업스트림 브랜치로 설정하여, 이후 푸시와 풀 작업 시 Git이 기본적으로 어디에 푸시하고 어디에서 풀해야 하는지 알 수 있게 합니다.

정리하자면,

1. 새로운 Git 저장소를 초기화.
2. 파일(README.md)을 스테이징 영역에 추가.
3. 스테이징된 파일을 저장소에 커밋.
4 .기본 브랜치를 main으로 이름을 변경.
5. 원격 저장소 URL을 추가.
6. 로컬 main 브랜치를 원격 저장소에 푸시하고 추적을 설정

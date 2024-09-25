# GIT&GitHub 명령어!!!

```
1. 기본 Git 명령어
```
### 설정 관련


```bash   
    git config --global user.name "이름" #사용자 이름 설정  

    git config --global user.email "이메일" #사용자 이메일(깃 허브 계정)   

    git config --list                      # 현재설정된 git 정보 확인
```

### 레포지토리 초기화 및 상태 확인

```bash   
    git init        #새로운 git 레포지토리 생성   

    git clone <URL> #원격 레포지토리 복제   

    git status      # 작업 디렉토리 상태 확인  

    git log         # 커밋 로그 확인   
```


### 스테이징 및 커밋
``` bash  
    git add <파일명>       # 툭정파일 스테이징  

    git add .             # 현재 디렉토리 모든 파일 스테이징  

    git commit -m "커밋 메세지"     # 스테이징된 파일 커밋   

    git diff            # 변경 사항 확인(스테이징 되지 않은 파일)   

    git diff --staged      # 스테이징된 변경 사항 확인   
```



###  원격 저장소 관련

```bash   
    git remote add origin <URL>         # 원격 레포지토리 추가   

    git remote -b                       # 설정된 원격 저장소 확인

    git remote remove origin            # 설정된 원격 저장소 제거
    
    git push origin main                # 변경 사항을 원격 저장소에 올리기

    git pull origin main                # 원격 저장소로 부터 변경 사항 가져오기

    git fetch                           # 원격 저장소의 최신 커밋정보 가져오기.
```



# hello-git-github
# Working Directory 생성부터 원격 저장소에 README.md 파일을 push 하기까지의 과정과 셸 명령어

1. 프로젝트 디렉토리로 이동:
   ```bash
   cd ~/Unix/git/hello-git
2. Git 저장소 초기화:
   ```bash
   git init
3. README.md 파일 생성:
  ```bash
  echo "# hello-git-github">README.md
  ```
4. README.md 파일을 스테이징 영역에 추가:
```bash
git add README.md
```
5.커밋 생성:
```bash
git commit -m "Add README.md"
```
6. 원격 저장소 추가:
```bash
git remote add origin https://github.com/shinhyobin/hello-git-github.git
```
7. 기본 브랜치 변경:
```bash
git branch -M main
```
8. 로컬 커밋을 원격 저장소에 푸시:
```bash
git push -u origin main
```


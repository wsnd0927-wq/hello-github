# 실습 기록 — GitHub 원격 저장소 생성과 업로드

`<GitHubID>` 부분만 자신의 GitHub 사용자명으로 바꾸면 그대로 실행할 수 있습니다.

## 1. 로컬 저장소 초기화

```bash
git init
```

## 2. 실습 파일 스테이징

```bash
git add .
git status
```

## 3. 커밋

```bash
git commit -m "Add practice files for hello-github assignment"
```

## 4. 기본 브랜치를 main 으로

```bash
git branch -M main
```

## 5. GitHub 원격 저장소 연결

```bash
git remote add origin https://github.com/<GitHubID>/hello-github.git
git remote -v
```

## 6. 업로드(푸시)

```bash
git push -u origin main
```

## 7. 결과 확인

```bash
git log --oneline
git ls-remote --heads origin
```

> 참고: GitHub에서 저장소를 만들 때 **Public** 으로 설정하고,
> `Add a README file` / `.gitignore` / `license` 는 체크하지 않아야
> 로컬 저장소와 충돌(비어 있지 않은 원격) 없이 푸시됩니다.

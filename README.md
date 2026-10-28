# hello-github

오픈소스 소프트웨어 수업 실습 과제 저장소입니다.

로컬 Git 저장소를 GitHub 원격 저장소(`hello-github`)에 연결하고, 실습 파일을
`commit` → `push` 한 결과를 담고 있습니다.

## 구성

| 파일 | 설명 |
| --- | --- |
| `hello.txt` | 첫 번째 실습 파일 (Hello, GitHub!) |
| `git-notes.md` | 실습에 사용한 Git 명령 정리 |
| `README.md` | 저장소 소개 (이 문서) |

## 업로드 절차

1. GitHub에서 `hello-github` 저장소를 **Public**으로 생성
2. 로컬 저장소 초기화 (`git init`) 및 커밋
3. 원격 저장소 연결 (`git remote add origin ...`)
4. 업로드 (`git push -u origin main`)

## 확인

```bash
git remote -v                # 원격 저장소 주소
git log --oneline            # 커밋 기록
git ls-remote --heads origin # 원격 브랜치 확인
```

---

Open source software practice repository. Local repository connected to the
GitHub remote `hello-github`; practice files committed and pushed to `main`.

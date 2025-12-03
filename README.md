## 자동저장되긴 하지만 Ctrl+S로 저장권장
## README.md는 검색엔진(GitHub & Google)에 기본적으로 모두 걸림
- 민감한 내용이 있으면 private으로 하거나 표현을 조정
- 방법1) private로 설정
- 방법2) README에서 검색 노출 막는 태그 넣기
    - Google에게 색인하지 말라고 명령:
    - <meta name="robots" content="noindex">
    - 하지만 GitHub는 README에서 meta 태그를 무시할 때가 많아서 확실하지는 않음.
- 방법3) 특정 단어를 흐리게 쓰기
  - 예: 이메일, 전화번호, 회사 내부 내용 등
- 색인 방지 목적이면 단어를 그대로 안 쓰는 방법도 있음.

---

# 프로젝트 제목 (Project Title)

프로젝트에 대한 간단한 설명을 여기에 작성합니다.

## Features
- 기능 1
- 기능 2
- 기능 3

## Folder Structure

## 샘플 readme.md
https://github.com/KpmgFuture-Academy/fa02_fin_MODI


## 현재작업은 Codespace 컨테이너에만 저장된 상태
- GitHub에 저장(Push)해야 진짜로 보관됨
- Codespace가 끝나고도 기록을 남기려면 Git commit + push 필요함.
- 하단의 터미널에서
  - git add .
  - git commit -m "작업 내용 저장"
  - git push




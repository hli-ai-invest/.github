# 🏦 hli-ai-invest

💡 투자AI팀 임시 레포입니다! 💡

## 🔑 환경변수 관리

- `.env`는 **절대 커밋 금지**
- `.env.example`에 키 이름만 정의하고 커밋 → 각자 복사해서 값만 채워 사용

```bash
cp .env.example .env   # 복사 후 실제 키 값 입력
```

## 📁 Repo 네이밍 규칙

| 접두사 | 용도 | 생성 | 예시 |
|--------|------|------|------|
| `toy-` | 토이 프로젝트 | 자유 생성 | `toy-morning-brief` |
| 없음 | 실제 프로젝트 | 팀 협의 후 생성 | `morning-brief-api` |

- 중복 시 이름 추가: `toy-morning-brief-jhlee`
- 소문자, 하이픈으로 연결

## 🛠 기술 스택

- **언어**: Python 3.13+
- **API**: FastAPI
- **패키지 매니저**: uv

## ⚡ 프로젝트 초기 세팅

```bash
gh api repos/hli-ai-invest/project-setup/contents/setup.sh -H "Accept: application/vnd.github.raw+json" | bash -s python
```

> ℹ️ private 레포이므로 [gh CLI](https://cli.github.com/)가 설치 및 인증(`gh auth login`)되어 있어야 합니다.

📦 상세 내용 및 변경 요청: [project-setup](https://github.com/hli-ai-invest/project-setup) (수정 시 PR 필수)

## 🚀 시작하기

1. org에 repo 생성 (네이밍 규칙 참고)
2. 위 세팅 스크립트 실행 (선택)
3. `CLAUDE.md`에서 프로젝트명/설명 수정 (선택)

# CLAUDE.md

이 프로젝트(work-agent)에서 Claude Code가 따라야 하는 추가 규칙.

capture-session rule 등 범용 규칙은 ~/.claude/CLAUDE.md에 있다.

## 브랜치 & PR 규칙

- 새 Agent / CLI 커맨드 / 계층 구조 변경은 반드시 `feat/` 또는 `refactor/` 브랜치에서 작업한다.
- 문서(md 파일)만 수정할 때는 main에서 직접 커밋해도 된다.
- GitHub API는 curl + `GITHUB_TOKEN`으로 호출한다 (`gh` CLI 사용 안 함).
- 커밋 메시지와 PR 본문에 AI 작성 표시(`Co-Authored-By`, `Generated with` 등)를 넣지 않는다.
- squash merge 기본 사용.

# B3-2 내가 고친 코드 설명을 AI가 대신 써주는 도우미 만들기

코딧세이 AI 올인원 본과정 B3-2 미션 저장소입니다.

## 범위
Python CLI·git diff 수집·AI API REST 연동·커밋 메시지/PR 초안 생성·키 .env 분리

## 개발 환경
Python 3.10 이상과 Git을 사용하는 터미널 프로그램입니다. API 키는 환경변수로 관리합니다.
필요한 의존성과 환경변수 이름은 연동 방식을 정한 뒤 기록합니다.

### 새 환경에서 준비

Git을 설치한 뒤 새 기기에서 저장소를 받습니다.

```bash
git clone https://github.com/sarguments/b3-2-ai-commit-helper.git
cd b3-2-ai-commit-helper
```

Python 3.10 이상을 설치한 뒤 저장소 루트에서 실행합니다. 가상환경은 기기마다 새로 만듭니다.

```bash
python3 --version
python3 -m venv .venv
.venv/bin/python --version
```

Git 명령도 `git --version`으로 확인합니다.

아직 실행할 기능 코드가 없습니다. 실행 명령과 외부 의존성은 실제 구현 후 기록합니다.

## 준비 상태
Python 3.14.3 가상환경을 준비했습니다. Git 변경 수집과 AI 호출 기능은 아직 구현하지 않았습니다.
결과물은 커밋 메시지와 PR 설명의 초안 텍스트이며 원격 자동 반영 기능은 포함하지 않습니다.

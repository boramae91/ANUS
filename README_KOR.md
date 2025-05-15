# 🍑 Anus: 자율 네트워크 유틸리티 시스템

<p align="center">
  <img src="assets/anus_logo.png" alt="Anus AI 로고" width="200"/>
</p>

<p align="center">
  <a href="https://github.com/nikmcfly/ANUS/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="라이센스: MIT"></a>
  <a href="https://www.python.org/downloads/"><img src="https://img.shields.io/badge/python-3.11+-blue.svg" alt="파이썬 버전"></a>
  <a href="https://github.com/psf/black"><img src="https://img.shields.io/badge/code%20style-black-000000.svg" alt="코드 스타일: black"></a>
  <a href="https://github.com/nikmcfly/ANUS/blob/main/CONTRIBUTING.md"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg" alt="기여 환영"></a>
  <br>
  <a href="https://github.com/nikmcfly/ANUS/stargazers"><img src="https://img.shields.io/github/stars/nikmcfly/ANUS.svg?style=social&label=Star" alt="GitHub 스타"></a>
  <a href="https://github.com/nikmcfly/ANUS/network/members"><img src="https://img.shields.io/github/forks/nikmcfly/ANUS.svg?style=social&label=Fork" alt="GitHub 포크"></a>
  <a href="https://github.com/nikmcfly/ANUS/issues"><img src="https://img.shields.io/github/issues/nikmcfly/ANUS.svg" alt="GitHub 이슈"></a>
  <a href="https://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs 환영"></a>
  <a href="https://anus-ai.github.io/docs"><img src="https://img.shields.io/badge/docs-latest-brightgreen.svg" alt="문서 상태"></a>
  <a href="https://t.me/goanus"><img src="https://img.shields.io/badge/Telegram-blue?logo=telegram&logoColor=white" alt="텔레그램"></a>
</p>

## 목차

- [소개](#-소개)
- [왜 Anus인가?](#-왜-anus인가)
- [기능 및 역량](#-기능-및-역량)
- [설치](#-설치)
- [빠른 시작](#-빠른-시작)
- [사용 예시](#-사용-예시)
- [문서](#-문서)
- [기여하기](#-기여하기)
- [커뮤니티](#-커뮤니티)
- [라이센스](#-라이센스)

## 🌟 소개

**Anus**(자율 네트워크 유틸리티 시스템)는 작업 자동화를 혁신하기 위해 설계된 강력하고 유연하며 접근하기 쉬운 오픈 소스 AI 에이전트 프레임워크입니다. 최신 AI 기술과 모범 사례를 기반으로 구축된 Anus는 차세대 AI 에이전트 프레임워크를 대표하며, 타의 추종을 불허하는 기능과 사용 용이성을 제공합니다.

Anus는 사용자가 다음과 같은 AI 에이전트를 만들 수 있게 합니다:
- 자연어 지시를 통해 복잡한 작업 실행
- 다중 에이전트 환경에서 협업하여 문제 해결
- 웹 서비스, 문서 및 코드와 상호작용
- 텍스트, 이미지 및 오디오를 포함한 다중 모달 입력 처리
- 다양한 도메인과 사용 사례에 적응

AI 기반 애플리케이션을 구축하려는 개발자, 에이전트 기반 시스템을 탐구하는 연구자, 또는 최신 AI 기술에 관심 있는 애호가 모두에게 Anus는 성공하는 데 필요한 도구와 유연성을 제공합니다.

## 💡 왜 Anus인가?

- **진정한 오픈 소스**: 장벽 없고, 초대 코드 없이, 순수한 오픈 소스의 장점
- **하이브리드 아키텍처**: 단일 에이전트의 단순함과 다중 에이전트의 힘을 결합
- **유연한 모델 지원**: OpenAI 모델, 오픈 소스 모델 또는 자체 모델과 함께 작동
- **종합적인 도구 생태계**: 웹 자동화, 문서 처리, 코드 실행 등
- **커뮤니티 중심 설계**: 기여와 확장을 위해 구축됨
- **투명한 운영**: 모든 에이전트 행동과 결정에 대한 명확한 설명
- **크로스 플랫폼**: 다양한 운영 체제와 환경에서 작동

## ✨ 기능 및 역량

### 🧠 고급 AI 에이전트 아키텍처

- **하이브리드 에이전트 시스템**: 작업 복잡성에 따라 단일 에이전트와 다중 에이전트 모드 간을 원활하게 전환
- **동적 작업 계획**: 복잡한 작업을 관리 가능한 단계로 분해하는 정교한 계획 시스템
- **적응형 리소스 할당**: 작업 요구 사항에 따라 계산 리소스를 지능적으로 할당
- **메모리 관리**: 대화 전반에 걸쳐 컨텍스트 유지를 위한 단기 및 장기 메모리 시스템
- **설명 가능한 행동**: 투명한 추론 및 의사 결정 프로세스

### 🤝 다중 에이전트 협업

- **전문화된 에이전트 역할**: 연구원, 코더, 기획자 등 사전 정의된 역할
- **사용자 정의 역할 생성**: 특정 기능과 지식을 갖춘 자체 에이전트 역할 정의
- **에이전트 간 통신**: 효율적인 에이전트 간 통신을 위한 구조화된 프로토콜
- **합의 메커니즘**: 에이전트 투표 및 합의를 통한 협업적 의사 결정
- **갈등 해결**: 에이전트 간 의견 불일치를 해결하기 위한 정교한 프로토콜

### 🛠️ 종합적인 도구 생태계

- **웹 상호작용**:
  - Playwright를 통한 전체 브라우저 자동화
  - 웹 스크래핑 및 데이터 추출
  - 양식 작성 및 제출
  - 인증 처리

- **정보 검색**:
  - 검색 엔진 통합
  - 위키피디아 접근
  - 뉴스 및 시사 소스
  - 전문 지식 베이스

- **문서 처리**:
  - PDF 파싱 및 분석
  - Office 문서 처리(Word, Excel, PowerPoint)
  - 이미지 인식 및 OCR
  - 데이터 추출 및 변환

- **코드 실행**:
  - 안전한 Python 실행 샌드박스
  - 다중 언어 지원
  - 패키지 관리
  - 출력 캡처 및 분석

- **다중 모달 처리**:
  - 이미지 분석 및 생성
  - 오디오 처리 및 전사
  - 비디오 분석 및 요약
  - 차트 및 그래프 해석

### 🔄 유연한 모델 통합

- **OpenAI API 지원**: GPT-4 및 최신 모델과의 원활한 통합
- **오픈 소스 모델**: Llama, Mistral 및 기타 오픈 소스 모델 지원
- **로컬 배포**: 개인 정보 보호 및 비용 절감을 위한 로컬 모델 실행
- **모델 전환**: 작업 요구 사항에 따라 적절한 모델 자동 선택
- **대체 메커니즘**: 대체 모델로 전환하여 API 문제를 우아하게 처리

### 👥 사용자 친화적 인터페이스

- **명령줄 인터페이스**: 터미널 사용자를 위한 간단하고 직관적인 명령
- **웹 인터페이스**: 시각적 상호작용을 위한 선택적 브라우저 기반 대시보드
- **API 통합**: 다른 응용 프로그램에 Anus를 임베드하기 위한 RESTful API
- **대화 기록**: 이전 대화 검토 및 계속
- **작업 모니터링**: 장기 실행 작업의 진행 상황 추적

### 🔒 개인 정보 보호 및 보안

- **로컬 실행**: 외부 API로 보내지 않고 민감한 데이터를 로컬에서 처리
- **API 키 관리**: API 키 및 자격 증명의 안전한 처리
- **권한 시스템**: 에이전트 기능에 대한 세분화된 제어
- **감사 로깅**: 모든 에이전트 행동에 대한 포괄적인 로깅
- **샌드박스 실행**: 신뢰할 수 없는 코드를 실행하기 위한 안전한 환경

### 🧩 확장성

- **플러그인 시스템**: 사용자 정의 플러그인으로 기능을 쉽게 확장
- **사용자 정의 도구**: 에이전트 기능을 확장하기 위한 자체 도구 생성
- **모델 어댑터**: 새로운 AI 모델 지원 추가
- **미들웨어**: 에이전트 워크플로우에 사용자 정의 처리 단계 삽입
- **이벤트 훅**: 에이전트 수명 주기의 특정 이벤트에 반응

## 🔧 설치

Anus AI는 다양한 사용자 선호도와 환경에 맞게 여러 설치 방법을 지원합니다.

### 전제 조건

- Python 3.11 이상
- pip (Python 패키지 설치자)
- Git

### 방법 1: Pip 설치 (사용자에게 권장)

```bash
# PyPI에서 설치
pip install anus-ai

# 설치 확인
anus --version
```

### 방법 2: 소스에서 설치 (개발자에게 권장)

```bash
# 저장소 복제
git clone https://github.com/nikmcfly/ANUS.git
cd ANUS

# 가상 환경 생성 및 활성화
python -m venv venv
source venv/bin/activate  # Windows에서: venv\Scripts\activate

# 개발 모드로 설치
pip install -e .

# 설치 확인
anus --version
```

### 방법 3: Docker 사용

```bash
# Docker 이미지 가져오기
docker pull anusai/anus:latest

# 컨테이너에서 Anus 실행
docker run -it anusai/anus:latest
```

### 방법 4: Conda 사용

```bash
# 새 conda 환경 생성
conda create -n anus python=3.11
conda activate anus

# Anus 설치
pip install anus-ai
```

### 플랫폼별 지침

#### Windows

```bash
# 필수 시스템 종속성 설치
pip install windows-curses

# 브라우저 자동화를 사용하는 경우
playwright install
```

#### macOS

```bash
# 필수 시스템 종속성 설치
brew install python@3.11

# 브라우저 자동화를 사용하는 경우
playwright install
```

#### Linux

```bash
# 필수 시스템 종속성 설치
sudo apt-get update
sudo apt-get install -y python3.11 python3.11-venv

# 브라우저 자동화를 사용하는 경우
playwright install
```

### 선택적 종속성

Anus에는 추가 종속성이 필요한 여러 선택적 기능이 있습니다:

```bash
# 문서 처리용
pip install anus-ai[documents]

# 브라우저 자동화용
pip install anus-ai[browser]

# 코드 실행용
pip install anus-ai[code]

# 모든 선택적 기능용
pip install anus-ai[all]
```

### 구성

설치 후 API 키로 Anus를 구성해야 합니다:

1. 구성 파일 생성:

```bash
anus init
```

2. 생성된 `.anus/config.yaml` 파일을 API 키로 편집:

```yaml
llm:
  provider: openai
  api_key: your_openai_api_key
  model: gpt-4o

# 선택 사항: 다른 제공자 구성
anthropic:
  api_key: your_anthropic_api_key

# 선택 사항: 도구별 설정 구성
browser:
  headless: true
```

## 🚀 빠른 시작

설치 후 바로 Anus를 사용할 수 있습니다:

```bash
# 간단한 작업으로 Anus 실행
anus run "인공지능에 대한 최신 뉴스 찾기"

# 대화형 모드로 실행
anus interactive

# 특정 구성 파일로 실행
anus run --config custom_config.yaml "이 기사 요약: https://example.com/article"
```

## 📋 사용 예시

### 기본 예시

#### 간단한 질문 응답

```python
from anus import Agent

# 단일 에이전트 생성
agent = Agent()

# 간단한 질문하기
response = agent.run("프랑스의 수도는 어디인가요?")
print(response)
```

#### 웹 검색

```python
from anus import Agent
from anus.tools import SearchTool

# 검색 기능이 있는 에이전트 생성
agent = Agent(tools=[SearchTool()])

# 정보 검색
response = agent.run("양자 컴퓨팅에 대한 최신 연구 찾기")
print(response)
```

#### 문서 분석

```python
from anus import Agent
from anus.tools import DocumentTool

# 문서 처리 기능이 있는 에이전트 생성
agent = Agent(tools=[DocumentTool()])

# PDF 문서 분석
response = agent.run("이 PDF 요약: /path/to/document.pdf")
print(response)
```

### 고급 예시

#### 다중 에이전트 협업

```python
from anus import Society, Agent

# 전문화된 에이전트 생성
researcher = Agent(role="researcher")
analyst = Agent(role="analyst")
writer = Agent(role="writer")

# 에이전트의 사회 생성
society = Society(agents=[researcher, analyst, writer])

# 협업을 통한 복잡한 작업 실행
response = society.run(
    "인공지능이 의료에 미치는 영향을 연구하고, " 
    "결과를 분석하고, 종합적인 보고서 작성"
)
print(response)
```

#### 브라우저 자동화

```python
from anus import Agent
from anus.tools import BrowserTool

# 브라우저 기능이 있는 에이전트 생성
agent = Agent(tools=[BrowserTool()])

# 웹 작업 수행
response = agent.run(
    "weather.com에 가서 뉴욕시의 향후 5일 날씨 예보를 확인하고, "
    "요약 표를 만드세요"
)
print(response)
```

#### 코드 생성 및 실행

```python
from anus import Agent
from anus.tools import CodeTool

# 코드 실행 기능이 있는 에이전트 생성
agent = Agent(tools=[CodeTool()])

# 코드 생성 및 실행
response = agent.run(
    "matplotlib을 사용하여 프랙탈 트리 시각화를 생성하는 Python 스크립트 생성"
)
print(response)
```

### 명령줄 인터페이스 예시

#### 작업 실행

```bash
# 간단한 정보 검색
anus run "도쿄의 인구는 얼마인가요?"

# 특정 매개변수가 있는 웹 검색
anus run --search-depth=3 "핵융합 에너지 연구의 최근 돌파구 찾기"

# 문서 처리
anus run --file=/path/to/report.pdf "이 보고서에서 모든 재무 데이터 추출"
```

#### 대화형 모드

```bash
# 대화형 세션 시작
anus interactive

# 대화형 모드에서 대화할 수 있습니다:
# > 인공지능의 역사에 대해 알려주세요
# > 이제 주요 AI 이정표의 타임라인을 만들어주세요
# > 이 타임라인의 시각화를 생성해주세요
```

#### 다중 에이전트 모드

```bash
# 여러 에이전트로 복잡한 작업 실행
anus run --mode=multi "재생 에너지 기술의 현재 상태를 연구, 분석 및 요약"

# 특정 에이전트 역할 지정
anus run --mode=multi --roles=researcher,analyst,writer "전기 자동차에 대한 포괄적인 시장 분석 생성"
```

### API 사용

```python
from anus.api import AnusAPI

# API 클라이언트 초기화
api = AnusAPI(api_key="your_api_key")

# 요청 보내기
response = api.process_task(
    task="지속 가능한 패션 스타트업을 위한 비즈니스 계획 생성",
    mode="multi",
    output_format="markdown"
)

# 응답 출력 또는 저장
print(response.result)
with open("business_plan.md", "w") as f:
    f.write(response.result)
```

### 고급 구성

```python
from anus import Agent, Config

# 사용자 정의 구성 생성
config = Config(
    llm={
        "provider": "anthropic",
        "model": "claude-3-opus",
        "temperature": 0.7,
    },
    memory={
        "type": "persistent",
        "path": "./agent_memory",
    },
    tools={
        "browser": {"headless": False},
        "code": {"sandbox": True},
    }
)

# 사용자 정의 구성으로 에이전트 생성
agent = Agent(config=config)

# 작업 실행
response = agent.run("기후 변화 데이터를 위한 대화형 데이터 시각화 생성")
print(response)
```

## 📚 문서

자세한 문서는 [문서 사이트](https://anus-ai.github.io/docs)를 방문하세요.

- [설치 가이드](https://anus-ai.github.io/docs/installation)
- [시작하기](https://anus-ai.github.io/docs/getting-started)
- [아키텍처 개요](https://anus-ai.github.io/docs/architecture)
- [API 참조](https://anus-ai.github.io/docs/api)
- [예시](https://anus-ai.github.io/docs/examples)
- [기여 가이드](https://anus-ai.github.io/docs/contributing)

## 👥 기여하기

커뮤니티의 기여를 환영합니다! Anus는 커뮤니티 중심으로 설계되었으며, 여러분의 의견은 모두에게 더 나은 프로젝트를 만드는 데 도움이 됩니다.

### 기여 방법

- **코드 기여**: 새로운 기능 구현, 버그 수정 또는 성능 향상
- **문서화**: 문서 개선 또는 확장, 예시 추가, 오타 수정
- **버그 신고**: 버그 신고 또는 개선 제안
- **기능 요청**: 새로운 기능 또는 개선 사항 제안
- **커뮤니티 지원**: 질문에 답변하고 다른 사용자 지원

### 기여 시작하기

1. **저장소 포크**

```bash
# GitHub에서 저장소를 포크한 다음 포크를 복제
git clone https://github.com/your-username/anus.git
cd anus
```

2. **개발 환경 설정**

```bash
# 가상 환경 생성 및 활성화
python -m venv venv
source venv/bin/activate  # Windows에서: venv\Scripts\activate

# 개발 종속성 설치
pip install -e ".[dev]"
```

3. **브랜치 생성**

```bash
# 기여를 위한 브랜치 생성
git checkout -b feature/your-feature-name
```

4. **변경 사항 적용**

- 코드 스타일 가이드라인 준수
- 새로운 기능에 대한 테스트 추가
- 필요한 경우 문서 업데이트

5. **테스트 실행**

```bash
# 테스트 스위트 실행
pytest

# 린팅 실행
flake8
mypy anus
```

6. **풀 리퀘스트 제출**

- 변경 사항을 포크에 푸시
- 브랜치에서 메인 브랜치로 풀 리퀘스트 제출
- 변경 사항과 관련된 이슈에 대한 명확한 설명 제공

### 코드 스타일 가이드라인

- Python 코드 스타일을 위해 [PEP 8](https://pep8.org/) 준수
- 모든 함수 매개변수 및 반환 값에 타입 힌트 사용
- 모든 함수, 클래스 및 모듈에 대한 문서 문자열 작성
- 함수를 집중적이고 작게 유지(가능한 경우 50줄 미만)
- 의미 있는 변수 및 함수 이름 사용

### 커밋 메시지 가이드라인

[Conventional Commits](https://www.conventionalcommits.org/) 사양을 따릅니다:

```
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

타입에는 다음이 포함됩니다:
- `feat`: 새로운 기능
- `fix`: 버그 수정
- `docs`: 문서 변경
- `style`: 코드 스타일 변경(서식 지정 등)
- `refactor`: 버그를 수정하거나 기능을 추가하지 않는 코드 변경
- `test`: 테스트 추가 또는 수정
- `chore`: 빌드 프로세스 또는 보조 도구 변경

### 풀 리퀘스트 프로세스

1. 적절한 경우 변경 사항에 대한 세부 정보로 README.md 또는 문서 업데이트
2. 변경 사항에 대한 세부 정보로 CHANGELOG.md 업데이트
3. PR은 Python 3.11 이상에서 작동해야 함
4. PR은 최소 한 명의 관리자의 승인이 필요함
5. 승인되면 관리자가 PR을 병합함

### 행동 강령

이 프로젝트는 [기여자 행동 강령](CODE_OF_CONDUCT.md)과 함께 제공됩니다. 이 프로젝트에 참여함으로써 귀하는 해당 조건을 준수하는 데 동의합니다.

## 🌐 커뮤니티

도움을 받고, 아이디어를 공유하고, 프로젝트에 기여하기 위해 커뮤니티에 가입하세요:

- [텔레그램 채널](https://t.me/goanus)

## 📝 라이센스

Anus는 [MIT 라이센스](LICENSE)로 출시됩니다.

```
MIT License

Copyright (c) 2025 Anus AI Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
``` 
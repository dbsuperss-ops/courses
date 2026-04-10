# Anthropic 프롬프트 엔지니어링 대화형 튜토리얼에 오신 것을 환영합니다

## 과정 소개 및 목표

이 과정은 Claude 내에서 최적의 프롬프트를 설계하는 방법에 대해 포괄적이고 단계적인 이해를 제공하기 위해 마련되었습니다.

**이 과정을 마친 후 여러분은 다음을 할 수 있게 됩니다**:
- 좋은 프롬프트의 기본 구조 마스터하기
- 일반적인 실패 사례를 인식하고 이를 해결하기 위한 '80/20' 기술 배우기
- Claude의 강점과 약점 이해하기
- 일반적인 유스케이스를 위해 처음부터 강력한 프롬프트 구축하기

## 과정 구조 및 내용

이 과정은 여러분이 직접 프롬프트를 작성하고 문제를 해결해 볼 수 있는 많은 기회를 제공하도록 구성되었습니다. 과정은 **연습 문제와 함께 9개의 장**으로 나누어져 있으며, 더욱 고급화된 방법에 대한 부록이 포함되어 있습니다. **장의 순서대로 과정을 진행**하는 것을 권장합니다.

**각 레슨의 하단에는 "Example Playground" 영역**이 있어 레슨의 예시를 자유롭게 실험해 보며 프롬프트를 변경하는 것이 Claude의 응답을 어떻게 바꾸는지 직접 확인할 수 있습니다. [정답지](https://docs.google.com/spreadsheets/d/1jIxjzUWG-6xBVIa2ay6yDpLyeuOh_hR_ZB75a47KX_E/edit?usp=sharing)도 제공됩니다.

참고: 이 튜토리얼은 가장 작고 빠르며 저렴한 모델인 Claude 3 Haiku를 사용합니다. Anthropic에는 Haiku보다 지능적인 [두 가지 다른 모델](https://docs.anthropic.com/claude/docs/models-overview)인 Claude 3 Sonnet과 Claude 3 Opus가 있으며, Opus가 가장 지능적입니다.

*이 튜토리얼은 [Anthropic의 Claude for Sheets 확장 프로그램을 사용하여 Google Sheets](https://docs.google.com/spreadsheets/d/19jzLgRruG9kjUQNKtCg1ZjdD6l6weA6qRXG5zLIAhC8/edit?usp=sharing)에서도 제공됩니다. 사용자 친화적인 해당 버전을 사용하는 것을 권장합니다.*

시작할 준비가 되셨다면 `01_Basic Prompt Structure`로 이동하여 진행하세요.

## 목차

각 장은 레슨과 연습 문제 세트로 구성됩니다.

### 초급 (Beginner)
- **제1장:** 기본 프롬프트 구조 (Basic Prompt Structure)

- **제2장:** 명확하고 직접적이기 (Being Clear and Direct)

- **제3장:** 역할 할당하기 (Assigning Roles)

### 중급 (Intermediate)
- **제4장:** 데이터와 지침 분리하기 (Separating Data from Instructions)

- **제5장:** 출력 형식 지정 및 Claude 대신 말하기 (Formatting Output & Speaking for Claude)

- **제6장:** 사전 인지 (단계별로 생각하기) (Precognition (Thinking Step by Step))

- **제7장:** 예시 사용하기 (Using Examples)

### 고급 (Advanced)
- **제8장:** 환각(Hallucinations) 피하기 (Avoiding Hallucinations)

- **제9장:** 복잡한 프롬프트 구축 (산업 유스케이스) (Building Complex Prompts (Industry Use Cases))
  - 처음부터 복잡한 프롬프트 작성 - 챗봇
  - 법률 서비스를 위한 복잡한 프롬프트
  - **연습 문제:** 금융 서비스를 위한 복잡한 프롬프트
  - **연습 문제:** 코딩을 위한 복잡한 프롬프트
  - 축하 및 다음 단계

- **부록:** 표준 프롬프팅 그 이상 (Beyond Standard Prompting)
  - 프롬프트 체이닝 (Chaining Prompts)
  - 도구 사용 (Tool Use)
  - 검색 및 검색 증강 (Search & Retrieval)
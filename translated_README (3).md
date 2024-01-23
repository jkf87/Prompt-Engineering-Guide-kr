# 프롬프트 엔지니어링 가이드

프롬프트 엔지니어링은 다양한 애플리케이션과 연구 주제에 언어 모델(LM)을 효율적으로 사용할 수 있도록 프롬프트를 개발하고 최적화하는 비교적 새로운 분야입니다. 프롬프트 엔지니어링 기술은 대규모 언어 모델(LLM)의 기능과 한계를 더 잘 이해하는 데 도움이 됩니다. 연구자들은 프롬프트 엔지니어링을 사용하여 질문 답변 및 산술 추론과 같은 일반적이고 복잡한 다양한 작업에서 LLM의 역량을 향상시킵니다. 개발자는 프롬프트 엔지니어링을 사용하여 LLM 및 기타 도구와 인터페이스하는 강력하고 효과적인 프롬프트 기술을 설계합니다.

프롬프트 엔지니어링에 대한 개발자들의 높은 관심에 힘입어 저희는 프롬프트 엔지니어링과 관련된 모든 최신 논문, 학습 가이드, 강의, 참고 자료 및 도구가 포함된 새로운 프롬프트 엔지니어링 가이드를 만들었습니다.

행복한 프롬프트!

---
LLM을 위한 프롬프트 엔지니어링 과정 ## 바로가기

높은 수요로 인해 Maven과 협력하여 새로운 [LLM을 위한 프롬프트 엔지니어링에 대한 코호트 기반 과정](https://maven.com/dair-ai/prompt-engineering-llms)을 제공하게 되었습니다.

Meta AI 및 Elastic과 같은 회사에서 근무하며 AI 및 LLM 분야에서 다년간의 경험을 쌓은 [Elvis Saravia](https://www.linkedin.com/in/omarsar/)가 이 과정의 강사로 참여합니다.

이 실습 과정에서는 대규모 언어 모델(LLM)로 효과적으로 작업하고 구축하기 위한 신속한 엔지니어링 기술/도구, 사용 사례, 연습 및 프로젝트를 다룹니다.

과거 수강생은 소프트웨어 엔지니어부터 링크드인, 아마존, JP모건 체이스 앤 코, 인튜이트, 피델리티 인베스트먼트, 코인베이스, 구루 등 다양한 조직의 AI 연구자 및 실무자에 이르기까지 다양합니다.

---
## 공지사항/업데이트

- 법학석사를 위한 프롬프트 엔지니어링에 대한 새로운 강좌가 발표되었습니다! [여기에서 등록하세요](https://maven.com/dair-ai/prompt-engineering-llms)!
- 이제 전문 교육, 컨설팅 및 강연과 같은 여러 [서비스](https://www.promptingguide.ai/services)를 제공합니다.
- 🌐 이제 12개 언어를 지원합니다! 더 많은 번역을 환영합니다.
- 👩‍🎓 2023년 6월에 학습자 수가 80만 명을 넘어섰습니다!
- 새로운 웹 버전의 가이드 [여기](https://www.promptingguide.ai/)를 출시했습니다.
- 2023년 2월 21일 해커 뉴스에서 1위를 달성했습니다.
- 프롬프트 엔지니어링 강의가 [여기](https://youtu.be/dOxUroR57xs)에서 시작되었습니다.

[디스코드 가입](https://discord.com/invite/SKgkVT8BGJ)

[트위터 팔로우](https://twitter.com/dair_ai)

[뉴스레터 구독](https://nlpnews.substack.com/)

---

## 가이드
새로운 웹사이트 [https://www.promptingguide.ai/](https://www.promptingguide.ai/)에서도 최신 가이드를 확인할 수 있습니다.

- [프롬프트 엔지니어링 - 소개](https://www.promptingguide.ai/introduction)
  - [프롬프트 엔지니어링 - LLM 설정](https://www.promptingguide.ai/introduction/settings)
  - [프롬프트 엔지니어링 - 프롬프트의 기본](https://www.promptingguide.ai/introduction/basics)
  - [프롬프트 엔지니어링 - 프롬프트 요소](https://www.promptingguide.ai/introduction/elements)
  - [프롬프트 엔지니어링 - 프롬프트 설계를 위한 일반적인 팁](https://www.promptingguide.ai/introduction/tips)
  - [프롬프트 엔지니어링 - 프롬프트의 예](https://www.promptingguide.ai/introduction/examples)
- [프롬프트 엔지니어링 - 기법](https://www.promptingguide.ai/techniques)
  - [프롬프트 엔지니어링 - 제로 샷 프롬프트](https://www.promptingguide.ai/techniques/zeroshot)
  - [프롬프트 엔지니어링 - 소수 샷 프롬프트](https://www.promptingguide.ai/techniques/fewshot)
  - [프롬프트 엔지니어링 - 생각의 연쇄 프롬프트](https://www.promptingguide.ai/techniques/cot)
  - [프롬프트 엔지니어링 - 자기 일관성](https://www.promptingguide.ai/techniques/consistency)
  - [프롬프트 엔지니어링 - 지식 프롬프트 생성](https://www.promptingguide.ai/techniques/knowledge)
  - [프롬프트 엔지니어링 - 생각의 나무(ToT)](https://www.promptingguide.ai/techniques/tot)
  - [프롬프트 엔지니어링 - 자동 추론 및 도구 사용(ART)](https://www.promptingguide.ai/techniques/art)
  - [프롬프트 엔지니어링 - 자동 프롬프트 엔지니어](https://www.promptingguide.ai/techniques/ape)
  - [프롬프트 엔지니어링 - 액티브 프롬프트](https://www.promptingguide.ai/techniques/activeprompt)
  - [프롬프트 엔지니어링 - 방향성 자극 프롬프트](https://www.promptingguide.ai/techniques/dsp)
  - [프롬프트 엔지니어링 - 리액트 프롬프트](https://www.promptingguide.ai/techniques/react)
  - [프롬프트 엔지니어링 - 멀티모달 CoT 프롬프트](https://www.promptingguide.ai/techniques/multimodalcot)
  - [프롬프트 엔지니어링 - 그래프 프롬프트](https://www.promptingguide.ai/techniques/graph)
- [프롬프트 엔지니어링 - 애플리케이션](https://www.promptingguide.ai/applications)
  - [프롬프트 엔지니어링 - 프로그램 지원 언어 모델](https://www.promptingguide.ai/applications/pal)
  - [프롬프트 엔지니어링 - 데이터 생성](https://www.promptingguide.ai/applications/generating)
  - [프롬프트 엔지니어링 - RAG용 합성 데이터 세트 생성](https://www.promptingguide.ai/applications/synthetic_rag)
  - [프롬프트 엔지니어링 - 타클링 생성 데이터 세트 다양성](https://www.promptingguide.ai/applications/generating_textbooks)
  - [프롬프트 엔지니어링 - 코드 생성](https://www.promptingguide.ai/applications/coding)
  - [프롬프트 엔지니어링 - 졸업생 직무 분류 사례 연구](https://www.promptingguide.ai/applications/workplace_casestudy)
- [프롬프트 엔지니어링 - 모델](https://www.promptingguide.ai/models)
  - [프롬프트 엔지니어링 - 플란](https://www.promptingguide.ai/models/flan)
  - [프롬프트 엔지니어링 - ChatGPT](https://www.promptingguide.ai/models/chatgpt)
  - [프롬프트 엔지니어링 - LLaMA](https://www.promptingguide.ai/models/llama)
  - [프롬프트 엔지니어링 - GPT-4](https://www.promptingguide.ai/models/gpt-4)
  - [프롬프트 엔지니어링 - 모델 컬렉션](https://www.promptingguide.ai/models/collection)
- [프롬프트 엔지니어링 - 위험 및 오용](https://www.promptingguide.ai/risks)
  - [프롬프트 엔지니어링 - 적대적 프롬프트](https://www.promptingguide.ai/risks/adversarial)
  - [프롬프트 엔지니어링 - 사실성](https://www.promptingguide.ai/risks/factuality)
  - [프롬프트 엔지니어링 - 편견](https://www.promptingguide.ai/risks/biases)
- [프롬프트 공학 - 논문](https://www.promptingguide.ai/papers)
  - [프롬프트 공학 - 개요](https://www.promptingguide.ai/papers#overviews)
  - [프롬프트 엔지니어링 - 접근법](https://www.promptingguide.ai/papers#approaches)
  - [프롬프트 엔지니어링 - 애플리케이션](https://www.promptingguide.ai/papers#applications)
  - [프롬프트 엔지니어링 - 컬렉션](https://www.promptingguide.ai/papers#collections)
- [프롬프트 엔지니어링 - 도구](https://www.promptingguide.ai/tools)
- [프롬프트 엔지니어링 - 노트북](https://www.promptingguide.ai/notebooks)
- [프롬프트 엔지니어링 - 데이터 세트](https://www.promptingguide.ai/datasets)
- [프롬프트 엔지니어링 - 추가 읽기](https://www.promptingguide.ai/readings)


---
## 강의

프롬프트 기법, 애플리케이션 및 도구에 대한 포괄적인 개요를 제공하는 1시간 분량의 강의를 게시했습니다.
- [동영상 강의](https://youtu.be/dOxUroR57xs)
- [코드가 포함된 노트북](https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/notebooks/pe-lecture.ipynb)
- [슬라이드](https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/lecture/Prompt-Engineering-Lecture-Elvis.pdf)

---
## 로컬에서 가이드 실행하기

예를 들어 새 번역이 올바르게 구현되었는지 확인하기 위해 로컬에서 가이드를 실행하려면 다음과 같이 해야 합니다:

1. 노드 설치 >=18.0.0
1. 시스템에 `pnpm`이 없는 경우 설치합니다. 자세한 지침은 [여기](https://pnpm.io/installation)를 참조하세요.
1. 의존성을 설치합니다: pnpm i next react-dom nextra nextra-theme-docs`.
1. pnpm dev`로 가이드를 부팅합니다.
2. http://localhost:3000/`에서 가이드를 찾아봅니다.

---
## 등장
저희가 소개된 곳들입니다:
- 월스트리트 저널 - [ChatGPT는 훌륭한 답변을 줄 수 있습니다. 하지만 올바른 질문을 하는 방법을 아는 경우에만](https://www.wsj.com/articles/chatgpt-ask-the-right-question-12d0f035)
- 포브스 - [엄마, 아빠, 저는 프롬프트 엔지니어가 되고 싶어요](https://www.forbes.com/sites/craigsmith/2023/04/05/mom-dad-i-want-to-be-a-prompt-engineer/?sh=7f1213159c8e)
- 마켓테크포스트 - [최고의 무료 프롬프트 엔지니어링 리소스 (2023)](https://www.marktechpost.com/2023/04/04/best-free-prompt-engineering-resources-2023/)


---
본 가이드를 업무에 활용하시는 경우 다음과 같이 인용해 주시기 바랍니다:

```
@article{Saravia_Prompt_Engineering_Guide_2022,
저자 = {Saravia, Elvis},
journal = {https://github.com/dair-ai/Prompt-Engineering-Guide},
month = {12},
title = {{프롬프트 엔지니어링 가이드}},
year = {2022}
}
```

## 라이선스

[MIT 라이선스](https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/LICENSE.md)


여기에 누락된 부분이 있다고 생각되면 언제든지 PR을 개설해 주세요. 피드백과 제안은 언제나 환영합니다. 이슈를 개설하세요!

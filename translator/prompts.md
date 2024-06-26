# Chat GPT로 번역 잘하기 - 상황별 최적 프롬프트 소개

###  상황 1 : 문법이 맞는지 제대로 확인

<details>
<summary>상황</summary>

    내가 번역한 문장이 문법적으로 정확한지 확인하고, 만약 틀렸으면 고치고 싶은 상황
- 원문 : 그녀는 오랜 시간 음악을 공부했습니다.
- 내가 번역한 문장 : She long time studied music.  
</details>
<details>
<summary>보통의 프롬프트</summary>

- 이 문장 문법 어때?
- 'She long time studied music.'
</details>
<details>
<summary>개선된 프롬프트</summary>

- 나는 번역이 문법적으로 정확할 뿐만 아니라, 영어권 청자들에게도 자연스럽게 잘 와닿게 하고 싶음
- 번역문의 문법을 검사하고 문법이 틀렸다면 왜 틀렸는지, 다음엔 안틀릴 수 있도록 이유를 설명해줘. 최대한 쉽게 설명해줘
- 그리고 더 자연스럽거나 매력적으로 들릴 수 있는 다른 표현을 3개 제안해줘
- 번역문 : 'She long time studied music.'
- 특히 원문의 느낌을 유지하면서 영어로 자연스럽게 들릴 수 있도록 하는 것이 중요해 . 원문은 '그녀는 오랜 시간 음악을 공부했습니다.'"여기서 정말 오랜시간 고생하면서 공부한 느낌도 강조하고 싶어 
</details>
<details>
<summary>개선된 프롬프트 (템플릿)</summary>

- 나는 번역이 문법적으로 정확할 뿐만 아니라, 영어권 청자들에게도 자연스럽게 잘 와닿게 하고 싶음.
- 번역문의 문법을 검사하고 문법이 틀렸다면 왜 틀렸는지, 다음엔 안틀릴 수 있도록 이유를 설명해줘. 최대한 쉽게 설명해줘
- 그리고 더 자연스럽거나 매력적으로 들릴 수 있는 다른 표현을 3개 제안해줘
- 번역문 : **[번역문장 삽입]**
- 특히 원문의 느낌을 유지하면서 영어로 자연스럽게 들릴 수 있도록 하는 것이 중요해 . 원문은 **[원문 삽입]**
- **[원문에서 살리고 싶은 느낌]** 도 강조하고 싶어
</details>

### 상황 2 : 내가 번역한 문장에서 용어들이 적절하게 사용되었는지 확인
<details>
<summary>상황</summary>

    문법뿐만 아니라 전반적으로 내가 번역한 문장이 괜찮은지, 용어들이 잘 번역된건지 확인

- 원문 : 행정안전부은 2024년 사용자 중심의 공공 웹·앱 사용자 인터페이스(UI)와 사용자 경험(UX) 혁신을 위해 12억원 규모의 예산을 투입하여 본격 개선한다.
- 번역한 문장 : The Ministry of Public Administration and Security will invest 1.2 billion won in budget to innovate user-based public web and app user interface (UI) and user experience (UX) in 2024 to improve it.

</details>
<details>
<summary>보통의 프롬프트</summary>

- 원문 : 행정안전부은 2024년 사용자 중심의 공공 웹·앱 사용자 인터페이스(UI)와 사용자 경험(UX) 혁신을 위해 12억원 규모의 예산을 투입하여 본격 개선한다.
- 번역 : The Ministry of Public Administration and Security will invest 1.2 billion won in budget to innovate user-based public web and app user interface (UI) and user experience (UX) in 2024 to improve it
- 내 번역 어때
</details>
<details>
<summary>개선된 프롬프트</summary>

원문 : 행정안전부은 2024년 사용자 중심의 공공 웹·앱 사용자 인터페이스(UI)와 사용자 경험(UX) 혁신을 위해 12억원 규모의 예산을 투입하여 본격 개선한다.

번역 : The Ministry of Public Administration and Security will invest 1.2 billion won in budget to innovate user-based public web and app user interface (UI) and user experience (UX) in 2024 to improve it.

- 내가 번역한 영어 문장 어때? 이상하면 이유를 알려줘
- 특히 사용자 경험 혁신, 사용자 중심, 공공 웹앱 같은 전문 용어들의 번역이 제대로 된게 맞는지 꼭 확인해주고 이유를 알려줘
- 번역을 개선할 수 있으면, 영어적으로 자연스럽게 표현해줘
- 이 글은 정부의 보도자료이기 떄문에 문장이 간결하고 정확하고 분명해야 해
- 개선된 번역문은 3가지 옵션을 주고, 왜 그렇게 번역했는지 이유도 설명해줘
- 그리고 그 중에서 가장 좋은 옵션을 선정해줘
</details>
<details>
<summary>개선된 프롬프트 (템플릿)</summary>

원문 : **[원문 삽입]**

번역한 문장 : **[번역문 삽입]**
- 번역 잘 된거 맞아? 체크해줘
- 특히 [**원문 전문용어 예시 나열]** 같은 전문 용어들의 번역이 제대로 된게 맞는지 꼭 확인해주고 이유를 알려줘
- 번역을 개선할 수 있으면, 영어적으로 자연스럽게 표현해줘
- 이 글은 **[원문 성격]** 이기 때문에 문장이 간결하고 정확하고 분명해야 해
- 개선된 번역문은 3가지 옵션을 주고, 왜 그렇게 번역했는지 이유도 설명해줘
- 그리고 그 중에서 가장 좋은 옵션을 선정해줘
</details>

### 상황 3 :  2개 비슷한 문장 사이에 고민

<details>
<summary>상황</summary>

    2개의 비슷한 번역문장이 있는데 어떤게 더 좋은지 고민을 하는 경우

- 원문 : 해당 장치는 인터넷에 쉽게 접근할 수 있도록 한다.
- 번역 1 : The device enables easy access to the internet.
- 번역 2 : The device facilitates easy access to the internet.  
</details>
<details>
<summary>보통의 프롬프트</summary>

- "이 두 문장 중 어떤게 낫니? '
- A: The device enables easy access to the internet. 
- B: The device facilitates easy access to the internet.'"
</details>
<details>
<summary>개선된 프롬프트</summary>
번역 1) The device enables easy access to the internet

번역 2) The device facilitates easy access to the internet.

- 두 번역 문장 중 어떤게 낫니?
- 원문 : 해당 장치는 인터넷에 쉽게 접근할 수 있도록 한다.
- 원문은 기술적 제품을 설명하는 글이다
- 특히 enable와 facilitate의 미묘한 차이를 구체적으로 설명해주고, 어떤 상황에서는 어떤 단어를 쓰는게 더 맞는지 추천해줘
- 두 번역문장 말고도 대안이 있으면 알려주고 이유를 설명해줘
</details>
<details>
<summary>개선된 프롬프트 (템플릿)</summary>

번역 1 : **[번역문 1 삽입]**

번역 2 : **[번역문 2 삽입]**

두 번역 문장 중 어떤게 낫니?
- 원문 : **[원문 삽입]**
- 원문은 **[원문 성격]** 글이다
- 특히 **[단어 차이]** 미묘한 차이를 구체적으로 설명해주고, 어떤 상황에서는 어떤 단어를 쓰는게 더 맞는지 추천해줘
- 두 번역문장 말고도 대안이 있으면 알려주고 이유를 설명해줘
</details>

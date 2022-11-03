# JOOC 관련 논문 정리
# Watch Less and Uncover More : Could Navigation Tools Help Users Search and Explore Videos?

## 개요 
[선행 연구] 
‘content preview tools’가 다양한 정보 검색 작업에서 사용자 관련성 판단의 속도와 정확도를 어떻게 향상시키는지 보여주었음.

위 논문에서는 새로운 사용자 인터페이스 도구인 ‘콘텐츠 흐름 막대 (the Content Flow Bar’)에 대해 설명함.
• ‘Content Flow Bar(CFB, 콘텐츠 흐름 막대)’란?
: 사용자가 인지적으로 강화된 형태의 탐색을 통해, 정보 비디오 내에서 탐색이 용이하도록 관련 조각을 빠르게 식별할 수 있게 설계된 것.

-> 의미론적 “snippets”을 제공함으로써 이를 달성함.
• ‘snippets(스니펫)’이란?
: 사용자가 비디오 콘텐츠를 빠르게 스캔할 수 있는 의미론적 도구.
-> snippets은 각 비디오 하단 시계열 표시줄에 나타나는 시각적으로 호소력 있는 팝업을 제공.
-> 콘텐츠에서 주제가 어떻게 발전하는지 한 눈에 미리 볼 수 있게 함.

• 사용자 연구 수행 목적
(1) snippets이 비디오 검색에서 사용자 검색 경험을 어떻게 변화시키는지, 
(2) snippets이 탐색과 정보 찾기를 어떻게 지원하는지를 평가하기 위함.
-> 설문을 통해 사용자들이 컨텐츠 흐름 막대(CFB)가 비디오에서 관련 정보를 찾는 데 유용하다는 결과를 얻음.
## CCS Concepts
• 정보 시스템 (Informational systems) -> 사용자 및 대화형 검색 (Users and interactive retrieval) ; 검색 인터페이스 (Search interfaces) ; 정보 추출 (informational extraction) ;
• 응용 컴퓨팅 (Applied computing) -> 대화형 학습 환경 (Interactive learning environments)

## 키워드
• 비디오 검색 (video retrieval)
• 사용자 인터페이스 (users interfaces)
• 상호작용 설계 (interaction design)
• 탐색 (navigation)
• 검색 개방형 교육 (search open education)
## 1. Introduction

• 정보 검색 작업의 주요 병목 현상 중 하나
= 사용자는 검색된 항목의 내용에만 연속적으로 엑세스 가능.
-> 이는 여러 자료를 처리하고, 긴 자료를 필터링하는 데에도 적용됨 !
Why? 사용자가 처음에 콘텐츠의 어떤 부분 (ex. 비디오)이 자신의 요구와 관련이 있는지 모를 수 있기 때문.
-> 따라서 ‘content previews’는 다양한 콘텐츠 유형 및/또는 정보 검색 작업에 걸쳐 사용자 관련성 판단의 속도 및 정확도를 향상시킬 수 있음.

• 문제점
① 검색 및 검색 도구에서 더 나은 탐색 도구를 만들 수 있는 잠재력이 사용되지 않음.
② 이러한 도구가 사용자 행동, 인식 및 검색 경험에 어떤 영향을 미치는지에 대한 분석 부족.

• 학생들을 위한 점점 더 있기 있는 접근법 
= 온라인에서 무료로 제공되는 비디오 강의를 시청하는 것 !
-> 사용자 (학생들) 선택의 어려움 문제 발생 !
Why? 이용 가능한 교육용 온라인 비디오 수의 기하급수적인 증가.

• 사용자 선택을 도와주는 방법은 ? (위 연구에서 다루는 주제)
학습자와 교사가 1) 잠재적으로 사용 가능한 수백만 개의 비디오 중에서 선택 /
2) 관련 교육 콘텐츠에 엑세스 할 수 있도록 지원하는 탐색 도구를 제안하고 평가함. 

-> 접근 방식
① 검색 쿼리와 일치하는 비디오 조각을 강조 표시
② 비디오의 처음에서 시작하는 대신 효과적인 진입점 (또는 대안 - 학습자의 정보 요구에 따라)으로 작용할 수 있는 시각화 도구를 설계하는 것.
• 연구 초점
: 교육 비디오에 대한 도구(콘텐츠 흐름 막대, CFB)가 사용자 행동과 정보 검색 경험에 어떻게 영향을 미치는지 평가하는 데 있음 ! 

• 도구(CFB) 평가를 위한 사용자 연구 수행 
: 두 가지 정보 찾기 작업을 가진 사용자 연구를 수행.
 (상호작용 로그와 정성적 조사 결과를 수집)
: 참가자들은 도구(CFB)를 사용하여 각 과제 질문에 가장 적합한 비디오를 결정.

① 정성적 조사 결과
-> 참가자의 82% 는 CFB가 비디오 클립을 더 쉽게 찾을 수 있다고 응답.
-> 약 93%는 더 많은 비디오 플레이어가 CFB를 포함해야 한다고 동의함.
-> 결과적으로 Content Flow Bar(=도구)가 사용자가 콘텐츠를 탐색하는 데 매우 유용하다는 것을 보여줌.

② 상호작용 로그
-> CFB 도구가 콘텐츠 시청 시간을 줄이고, 
-> 비디오 내부와 비디오 전반에 걸쳐 더 많은 탐색을 하며, 
-> 열린 비디오당 체류 시간을 줄인다는 것을 추가로 보여줌.

## 2. Related Work
제안한 도구 (Content Flow Bar, CFB)는 지능형 사용자 인터페이스 구성 요소와 인공지능을 사용
-> 비디오의 효율적인 미리 보기 및 비선형 소비를 개선하려고 시도 

[이 섹션에서는 작업에 영감을 준 정보 검색(IR, 섹션 2.1) 및 비디오 검색(섹션 2.2)에서 몇 가지 관련 기여를 식별]

### 2.1 Informational Search and Retrieval
• IR 시스템 설계의 핵심 목표
: 문서 간/내부를 검색하는 관련 정보를 찾는 사용자의 작업을 용이하게 하는 것.

• 사용자는 주로 검색 상호 작용 프로세스 동안 텍스트 및 시각적 단서 (ex. 제목, 스니펫(쿼리 종속 텍스트 요약[42], 설명 및 미리 보기)에 의존 

• 상용 검색 엔진도 쿼리 단어를 강조하는 등의 기술을 사용[42]. 
• 제안된 도구 (CFB)는 이러한 학습을 통합하기 위해 여러 텍스트 대기열을 활용.

• 향상된 투명성, 인간적으로 직관적인 측면 및 상세한 메타데이터/요약 모두 사용자가 자료를 선택하는 데 일관되게 도움이 된다는 것이 입증됨.[1].
-> [예시]
: 검색 결과의 효율적인 요약을 통해 사용자는 더 높은 등급의 문서에 액세스 가능.
 즉, 탐색을 강화할 수 있음[32, 41]. 

• IR 검색 인터페이스 개발 사례
: 코르티노비스 외 연구진[15]은 키워드에 대한 문서의 정렬 및 유사성 기반 문서 그룹화와 같은 보충 정보를 통합하여 구글과 유사한 IR 검색 인터페이스를 개발함.

-> 이 연구는 이러한 혼합 검색 경험이 중요함을 보여줌.
Why? 교육 IR 설정에서 사용자가 검색하는 주제에 대해 완전히 익숙하지 않을 수 있기 때문.

-> 이는 교육적인 시나리오에서 사용자가 내용을 더 잘 이해하기 위해 검색 결과를 확장할 수 있도록 허용하는 것이 바람직할 수 있음을 의미.

[정리]
① 효율적인 미리 보기 기능을 갖는 것
-> 검색에서 사용자 관련성 판단에 중요한 것으로 입증.

② 텍스트(설명)의 정적 요약 생성에서 보다 최근의 쿼리 기반 요약에 이르기까지, 
-> 두 경우 모두 "사용자가 각 문서에 포함된 관련 정보를 보다 쉽게 식별할 수 있도록 지원"
-> 결과 관련성의 속도와 정확도를 향상시키는 것으로 나타남[34]. 

③ 정보를 미리 볼 때, 
WordClouds(단어 클러스터) [36] 및 TileBars(단어 존재 표현과 같은 열 지도) [19]와 같은 방법은
-> 1) 텍스트 정보를 줄이고 
   2) 키워드 순위(WordCloud의 단어 크기 및 TileBar의 색상 강도)를 강조
-> 빠른 시각적 표현(크기, 색상 등을 사용하는)을 가능하게 함.

④ 우리의 접근 방식은 내용을 요약하기 위해 개념 주석을 사용
-> But, 관련성 판단의 속도와 정확성을 활용하기 위해 비디오 단편 내에서 권한을 나타내는 개념의 순위를 매긴다.
### 2.2 Judging Relevance in Infomational Videos

• 정보 비디오 검색의 구체적 사례 분석
① 비디오 내의 탐색은 텍스트만큼 간단하지 않음.
Why? 정보는 비디오 프레임에 내장되어 종종 순차적으로 소비되기 때문.

-> 그러나 비디오 콘텐츠를 미리 볼 때, 일반적으로 제목 및 설명과 같은 측면 정보는 의미론적으로 관련된 섬네일을 만들기 위해 사용됨 [35, 40]

• 애니메이션 섬네일 그리드[20] 및 수많은 진행 표시줄 기반 “skimming” 접근 방식과 같은 변형은 YouTube 또는 Netflix와 유사한 미리 보기를 생성함 [11, 26].

• “skimming”은 교육 비디오를 미리 볼 때 젊은 성인 자기 주도 학습자 사이에서 일반적인 전략인 것으로 밝혀졌다[25]. 

② 비디오를 미리 보는 것이 주로 섬네일로 연상되는 동안, 연구는 텍스트 메타데이터와 미리 보기 모두를 사용하는 것이 더 효율적인 관련성 판단으로 이어진다는 것을 보여준다[16].
-> 이러한 발견을 기반으로 메타데이터, 스크립트 기반 개념 주석 및 미리 보기를 사용하여 효율적인 미리 보기 및 탐색을 개선한다. 

• 여러 기술은 IR을 개선하기 위해 비디오의 주석을 사용하는 것을 탐구했다. 

• 이들 중 일부는 크라우드 소싱을 사용하여 시간 지정 메타데이터[30] 및 비디오 조각 개념 주석[28, 31]과 같은 비디오 정보를 수집하는데, 이는 상당한 인력 없이는 확장 가능하지 않다.

• 이를 위해 비디오 검색 작업을 위해 신경 [27] 및 의미 기반 [39] 자동 비디오 표현 도구가 제안되었다. 

• 한계 : 그러나 이러한 기법 중 어느 것도 관련성 판단을 위한 비디오 미리보기의 유용성 측면에서 연구되지 않았다. 

YouTube Chapters(비디오 세그먼트에 대한 텍스트 제목)도 최근에 자동화된 비디오 조각 주석을 가지고 있습니다. 이 도구는 비디오 내에서 비선형 탐색을 허용하지만, 우리의 접근 방식은 비디오 검색 결과를 탐색할 때 스마트 미리 보기를 허용한다. 즉, 비디오를 선택하기 전에 사용할 수 있다.

 또한 YouTube Chapters는 비디오 프레임에서 텍스트를 식별하기 위해 광학 문자 인식을 사용하여 프레젠테이션과 같은 (슬라이드 쇼) 비디오에 대한 접근을 제한한다. 

도구의 설계 및 실험 결과는 공개되지 않아 성공 평가를 제한한다.

이러한 도구와 달리, 우리의 아이디어는 위키백과 주제[4]를 사용하여 자동 개념 주석을 활용하므로 사용자가 위키백과 정의[15]를 통해 검색 중에 낯선 주제에 대한 지식을 확장할 수 있으며 스크립트 기반이므로 모든 유형의 정보 비디오로 작업할 수 있다.

사용자 연구는 또한 제안된 지능형 비디오 미리보기 도구에 대해 매우 필요한 사용적합성 평가를 제공하여 정보 비디오 검색에서 탐색 도구의 잠재력을 보여준다.

<p align="center">
<img width="900" src="https://user-images.githubusercontent.com/100738522/199800180-c1fddd54-32b4-496a-91fa-a5bd8b0d7a59.png" alt="[그림1]">
</p>

[그림 1] CFB가 통합된 플랫폼(X5Learn)으로, 검색 시 비디오와 PDF 문서에 모두 액세스 가능.
※ 결과
• 파란색 상자에 검색란이 표시.
• 보라색 상자에는 관련 내용이 노란색으로 강조 표시된 CFB가 표시.
• 마지막 상자(초록색)는 CFB 계단식 메뉴를 표시.
-> 이것은 비디오에서 다루는 주제를 보여주며 해당 항목의 정의를 찾을 수 있음.

○ 주의 
사용자 연구를 위해 플랫폼의 많은 기능이 비활성화 되었음.
Ex. 기능으로서의 검색 비활성화 : 원인
  -> 참가자는 관련성 강조 표시 (CFB에서 노란색으로 표시)에 엑세스 불가 : 결과
  
  ## 3. The Visual Navigation Tool
• 정보 탐색을 용이하게 하는 새로운 시각적 미리 보기 도구인 ‘콘텐츠 흐름 막대 (CFB)’를 제시
• ‘콘텐츠 흐름 막대 (the Content Flow Bar, CFB)’
① 상호 작용 기술
② 검색과 탐색 모두 유용하도록 의도되었음.
③ 비디오 콘텐츠의 의미론적 “snippets”을 제공하도록 설계됨.

• ‘스니펫 (snippets)’
: 1) 팝업으로 표시되고 2)시계열 표시줄에 겹쳐 
 사용자가 비디오에서 다루는 주제를 미리 볼 수 있음.

• (CFB) 설계 근거
CFB는 충분한 디테일을 제공할 수 있는 가벼운 도구임 !
-> 팝업 키워드가 인식된 요구와 일치하는지 확인하기 위해 비디오 섬네일을 훑어보는 동안 힐끗 볼 수 있음 ! 

• 다음 단계
: 디자인 원칙과 사용 맥락, 팝업 키워드인 위키화를 추출하기 위한 근간과 함께 CFB 소개

### 3.1 Context of Use
### 3.2 Content Flow Bar (CFB)
### 3.3 Wikification to Extract Keywords

## 4. User Evaluation

### 4.1 Controlled User Study
### 4.2 Goal of Study and Research Questions
### 4.3 Experimental Design and Procedure
### 4.4 Participants
### 4.5 Click Stream and Interaction Log Analysis
### 4.6 Statistical Analysis

## 5. Effect of CFB User Interaction Behaviours and Perceptions
### 5.1 Differences Across Tasks
### 5.2 Time Spent
### 5.3 Users Activity
### 5.4 Users Navigation
### 5.5 Selecting Relevant Content
### 5.6 Users Perception of the CFB

## 6. Discussion and Conclusions
## 7. Acknowledgments
## 8. References

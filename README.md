# JOOC 관련 논문 정리
# Watch Less and Uncover More : Could Navigation Tools Help Users Search and Explore Videos? [Link](https://arxiv.org/abs/2201.03408)

## - 개요 
> **[선행 연구] = ‘content preview tools’** 가 다양한 정보 검색 작업에서 **사용자 관련성 판단의 속도와 정확도를 어떻게 향상**시키는지 보여줌.<br/>
<br/>

위 논문에서는 **새로운 사용자 인터페이스 도구인 ‘콘텐츠 흐름 막대 (the Content Flow Bar)'** 에 대해 설명

- **‘Content Flow Bar(CFB, 콘텐츠 흐름 막대)’** 란?<br/>
: 사용자가 인지적으로 강화된 형태의 탐색을 통해,  
정보 비디오 내에서 탐색이 용이하도록 관련 조각을 빠르게 식별할 수 있게 설계된 것<br/>

   - 의미론적 'snippets'을 제공함으로써 이를 달성<br/><br/>
   
- **‘snippets(스니펫)’** 이란?<br/>
: 사용자가 비디오 콘텐츠를 빠르게 스캔할 수 있는 의미론적 도구<br/>
   - snippets은 각 비디오 하단 시계열 표시줄에 나타나는 시각적으로 호소력 있는 팝업을 제공<br/>
   - 콘텐츠에서 주제가 어떻게 발전하는지 한 눈에 미리 볼 수 있게 함<br/><br/>
   
- **사용자 연구 수행 목적** <br/>
   - snippets이 비디오 검색에서 사용자 검색 경험을 어떻게 변화시키는지,  
   - snippets이 탐색과 정보 찾기를 어떻게 지원하는지를 평가하기 위함<br/><br/>
   = 설문을 통해 사용자들이 **컨텐츠 흐름 막대(CFB)가 비디오에서 관련 정보를 찾는 데 유용**하다는 결과를 얻음.
## - CCS Concepts
• 정보 시스템 (Informational systems)  
-> 사용자 및 대화형 검색 (Users and interactive retrieval) ; 검색 인터페이스 (Search interfaces) ; 정보 추출 (informational extraction) ;   

• 응용 컴퓨팅 (Applied computing) -> 대화형 학습 환경 (Interactive learning environments)

## - 키워드
• 비디오 검색 (video retrieval)  

• 사용자 인터페이스 (users interfaces)  

• 상호작용 설계 (interaction design)  

• 탐색 (navigation)  

• 검색 개방형 교육 (search open education) 

---
## 1. Introduction

- **정보 검색 작업의 주요 병목 현상** 중 하나는 ?<br/>
: 사용자는 **검색된 항목의 내용에만 연속적으로 엑세스 가능**<br/>
   - 이는 여러 자료를 처리하고, 긴 자료를 필터링하는 데에도 적용됨 !<br/><br/>
**Why?** 사용자가 처음에 콘텐츠의 어떤 부분 (ex. 비디오)이 자신의 요구와 관련이 있는지 모를 수 있기 때문.<br/>
   - 따라서 ‘content previews’는 다양한 콘텐츠 유형 및/또는 정보 검색 작업에 걸쳐 사용자 관련성 판단의 속도 및 정확도를 향상시킬 수 있음.<br/><br/>

- **문제점**<br/><br/>
① 검색 및 검색 도구에서 더 나은 탐색 도구를 만들 수 있는 잠재력이 사용되지 않음.<br/><br/>
② 이러한 도구가 사용자 행동, 인식 및 검색 경험에 어떤 영향을 미치는지에 대한 분석 부족.<br/><br/>

- 학생들을 위한 **점점 더 있기 있는 접근법**<br/> 
: 온라인에서 무료로 제공되는 비디오 강의를 시청하는 것 !<br/>
   - 사용자 (학생들) 선택의 어려움 문제 발생 !<br/>
**Why?** 이용 가능한 교육용 온라인 비디오 수의 기하급수적인 증가.<br/><br/>

- **사용자 선택을 도와주는 방법은 ?** (위 연구에서 다루는 주제)<br/><br/>
학습자와 교사가 **(1) 잠재적으로 사용 가능한 수백만 개의 비디오 중에서 선택 <br/>
(2) 관련 교육 콘텐츠에 엑세스 할 수 있도록 지원하는 탐색 도구를 제안하고 평가**<br/> 

   - **접근 방식**<br/>
   ① 검색 쿼리와 일치하는 비디오 조각을 강조 표시<br/>
   ② 비디오의 처음에서 시작하는 대신 효과적인 진입점 (또는 대안 - 학습자의 정보 요구에 따라)으로 작용할 수 있는 시각화 도구를 설계하는 것.<br/><br/>
      
- **연구 초점**<br/>
: 교육 비디오에 대한 도구(콘텐츠 흐름 막대, CFB)가 사용자 행동과 정보 검색 경험에 어떻게 영향을 미치는지 평가하는 데 있음 !<br/><br/>

- **도구(CFB) 평가를 위한 사용자 연구 수행**<br/> 
: **두 가지 정보 찾기 작업**을 가진 사용자 연구를 수행.<br/>
 (상호작용 로그와 정성적 조사 결과를 수집)<br/><br/>
: 참가자들은 **도구(CFB)를 사용하여 각 과제 질문에 가장 적합한 비디오를 결정**<br/>

    **① 정성적 조사 결과** <br/>
    - 참가자의 82% 는 CFB가 비디오 클립을 더 쉽게 찾을 수 있다고 응답.<br/>
    - 약 93%는 더 많은 비디오 플레이어가 CFB를 포함해야 한다고 동의함.<br/>
    - 결과적으로 Content Flow Bar(=도구)가 사용자가 콘텐츠를 탐색하는 데 매우 유용하다는 것을 보여줌.<br/>

    **② 상호작용 로그**<br/>
    - CFB 도구가 콘텐츠 시청 시간을 줄이고,<br/> 
    - 비디오 내부와 비디오 전반에 걸쳐 더 많은 탐색을 하며,<br/>
    - 열린 비디오당 체류 시간을 줄인다는 것을 추가로 보여줌.<br/>

---
## 2. Related Work
**제안한 도구 (Content Flow Bar, CFB)는 지능형 사용자 인터페이스 구성 요소와 인공지능을 사용**  
-> 비디오의 효율적인 미리 보기 및 비선형 소비를 개선하려고 시도<br/><br/> 

[이 섹션에서는 작업에 영감을 준 정보 검색(IR, 섹션 2.1) 및 비디오 검색(섹션 2.2)에서 몇 가지 관련 기여를 식별]<br/><br/><br/>

### 2.1 Informational Search and Retrieval
- IR 시스템 설계의 핵심 목표<br/>
: 문서 간/내부를 검색하는 관련 정보를 찾는 사용자의 작업을 용이하게 하는 것.<br/><br/>

- 사용자는 주로 검색 상호 작용 프로세스 동안 텍스트 및 시각적 단서 (ex. 제목, 스니펫(쿼리 종속 텍스트 요약[42], 설명 및 미리 보기)에 의존<br/><br/> 

- 상용 검색 엔진도 쿼리 단어를 강조하는 등의 기술을 사용[42]. <br/><br/>
- 제안된 도구 (CFB)는 이러한 학습을 통합하기 위해 여러 텍스트 대기열을 활용.<br/><br/>

- 향상된 투명성, 인간적으로 직관적인 측면 및 상세한 메타데이터/요약 모두 사용자가 자료를 선택하는 데 일관되게 도움이 된다는 것이 입증됨.[1].<br/>
   - [예시]<br/>
   : 검색 결과의 효율적인 요약을 통해 사용자는 더 높은 등급의 문서에 액세스 가능.<br/>
   즉, 탐색을 강화할 수 있음[32, 41].<br/><br/> 

- IR 검색 인터페이스 개발 사례<br/>
: 코르티노비스 외 연구진[15]은 키워드에 대한 문서의 정렬 및 유사성 기반 문서 그룹화와 같은 보충 정보를 통합하여 구글과 유사한 IR 검색 인터페이스를 개발함.<br/>

   - 이 연구는 이러한 혼합 검색 경험이 중요함을 보여줌.<br/>
   Why? 교육 IR 설정에서 사용자가 검색하는 주제에 대해 완전히 익숙하지 않을 수 있기 때문.<br/><br/>

**= 이는 교육적인 시나리오에서 사용자가 내용을 더 잘 이해하기 위해 검색 결과를 확장할 수 있도록 허용하는 것이 바람직할 수 있음을 의미.**<br/><br/>

#### [정리]
① 효율적인 미리 보기 기능을 갖는 것<br/>
   - 검색에서 사용자 관련성 판단에 중요한 것으로 입증.<br/><br/>

② 텍스트(설명)의 정적 요약 생성에서 보다 최근의 쿼리 기반 요약에 이르기까지, <br/>
   - 두 경우 모두 "사용자가 각 문서에 포함된 관련 정보를 보다 쉽게 식별할 수 있도록 지원"<br/>
   - 결과 관련성의 속도와 정확도를 향상시키는 것으로 나타남[34]. <br/>

③ 정보를 미리 볼 때, WordClouds(단어 클러스터) [36] 및 TileBars(단어 존재 표현과 같은 열 지도) [19]와 같은 방법<br/>
   - 텍스트 정보를 줄이고 <br/>
   - 키워드 순위(WordCloud의 단어 크기 및 TileBar의 색상 강도)를 강조<br/>
      빠른 시각적 표현(크기, 색상 등을 사용하는)을 가능하게 함.<br/><br/>

④ 우리의 접근 방식은 내용을 요약하기 위해 개념 주석을 사용<br/>
   - But, 관련성 판단의 속도와 정확성을 활용하기 위해 비디오 단편 내에서 권한을 나타내는 개념의 순위를 매긴다.<br/><br/><br/>
### 2.2 Judging Relevance in Infomational Videos

### 정보 비디오 검색의 구체적 사례 분석 <br/> 
① 비디오 내의 탐색은 텍스트만큼 간단하지 않음. <br/> 
Why? 정보는 비디오 프레임에 내장되어 종종 순차적으로 소비되기 때문. <br/><br/>  

- 그러나 **비디오 콘텐츠를 미리 볼 때,** <br/> 
일반적으로 제목 및 설명과 같은 **측면 정보**는 의미론적으로 **관련된 섬네일을 만들기 위해 사용**됨[35, 40].<br/> 

- 애니메이션 섬네일 그리드[20] 및 수많은 진행 표시줄 기반 “skimming” 접근 방식과 같은 변형은 YouTube 또는 Netflix와 유사한 미리 보기를 생성함[11, 26].<br/> 

- **"skimming"** 은 **교육 비디오를 미리 볼 때 젊은 성인 자기 주도 학습자 사이에서 일반적인 전략**인 것으로 밝혀짐[25]. <br/><br/><br/>   

② **연구는 텍스트 메타데이터와 미리 보기 모두를 사용하는 것이 더 효율적인 관련성 판단으로 이어진다**는 것을 보여줌[16].<br/> 
   - **when?** 비디오를 미리 보는 것이 주로 섬네일로 연상되는 동안 <br/><br/>  
-> 이러한 발견을 기반으로 **메타데이터, 스크립트 기반 개념 주석 및 미리 보기를 사용하여 효율적인 미리 보기 및 탐색을 개선**<br/><br/>  

- 여러 기술은 IR을 개선하기 위해 비디오의 주석을 사용하는 것을 탐구.<br/><br/>  

- 이들 중 일부는 크라우드 소싱을 사용하여 시간 지정 메타데이터[30] 및 비디오 조각 개념 주석[28, 31]과 같은 비디오 정보를 수집하는데, 이는 상당한 인력 없이는 확장 불가능.<br/><br/>  

- 이를 위해 비디오 검색 작업을 위해 신경 [27] 및 의미 기반 [39] 자동 비디오 표현 도구가 제안됨. <br/><br/>  

- **한계** : 그러나 이러한 기법 중 어느 것도 **관련성 판단을 위한 비디오 미리보기의 유용성 측면에서 연구되지 않음.** <br/><br/><br/>   

③ **YouTube Chapters(비디오 세그먼트에 대한 텍스트 제목)**
- 이는 최근 자동화된 비디오 조각 주석을 가지고 있음.
- 이 도구는 비디오 내에서 비선형 탐색을 허용하나, 우리의 접근 방식은 **비디오 검색 결과를 탐색할 때 스마트 미리 보기를 허용**<br/><br/> 

= 즉, 비디오를 선택하기 전에 사용 가능 <br/> <br/> 
=  YouTube Chapters는 비디오 프레임에서 텍스트를 식별하기 위해 광학 문자 인식을 사용하여 프레젠테이션과 같은 (슬라이드 쇼) 비디오에 대한 접근을 제한 <br/><br/>  

- **문제점** <br/> 
: 도구(YouTube Chapters)의 설계 및 실험 결과는 공개되지 않아 성공 평가를 제한<br/> <br/> 

- **본 연구 아이디어의 장점 [ 도구(YouTube Chapters)와 비교했을 때 ]** <br/> 
   - **위키백과 주제**[4]를 사용하여 **자동 개념 주석을 활용** <br/> 
    -> **사용자**가 **위키백과 정의[15]를 통해** 검색 중에 **낯선 주제에 대한 지식을 확장**할 수 있음 <br/> 
   - **스크립트 기반**이므로 **모든 유형의 정보 비디오로 작업 가능** <br/><br/>  

- 사용자 연구는 또한 제안된 **지능형 비디오 미리보기 도구**에 대해 **매우 필요한 사용적합성 평가를 제공**하여 **정보 비디오 검색에서 탐색 도구의 잠재력을 보여줌.**<br/> 

![그림1](https://user-images.githubusercontent.com/100738522/199810957-98370032-5d88-4a42-83c6-a94e2c94f075.png)

**[그림 1] CFB가 통합된 플랫폼(X5Learn)으로, 검색 시 비디오와 PDF 문서에 모두 액세스 가능** <br/><br/>
**※결과**<br/>
- 파란색 상자에 검색란이 표시.<br/>
- 보라색 상자에는 관련 내용이 노란색으로 강조 표시된 CFB가 표시.<br/>
- 마지막 상자(초록색)는 CFB 계단식 메뉴를 표시.<br/>
   - 이것은 비디오에서 다루는 주제를 보여주며 해당 항목의 정의를 찾을 수 있음.

**※주의**<br/>
- 사용자 연구를 위해 플랫폼의 많은 기능이 비활성화 되었음.<br/>
- [예시]
   - 기능으로서의 검색 비활성화 : 원인<br/>
   - 참가자는 관련성 강조 표시 (CFB에서 노란색으로 표시)에 엑세스 불가 : 결과<br/><br/><br/>
  
---
  ## 3. The Visual Navigation Tool
- 정보 탐색을 용이하게 하는 새로운 시각적 미리 보기 도구인 ‘콘텐츠 흐름 막대 (CFB)’를 제시<br/><br/>
- ‘콘텐츠 흐름 막대 (the Content Flow Bar, CFB)’<br/>
① 상호 작용 기술<br/>
② 검색과 탐색 모두 유용하도록 의도되었음.<br/>
③ 비디오 콘텐츠의 의미론적 “snippets”을 제공하도록 설계됨.<br/><br/>

- ‘스니펫 (snippets)’<br/>
: 1) 팝업으로 표시되고 2)시계열 표시줄에 겹쳐 
 사용자가 비디오에서 다루는 주제를 미리 볼 수 있음.<br/><br/>

- (CFB) 설계 근거<br/>
: CFB는 충분한 디테일을 제공할 수 있는 가벼운 도구임 !<br/>
   - 팝업 키워드가 인식된 요구와 일치하는지 확인하기 위해 비디오 섬네일을 훑어보는 동안 힐끗 볼 수 있음 !<br/><br/> 

- 다음 단계<br/>
: 디자인 원칙과 사용 맥락, 팝업 키워드인 위키화를 추출하기 위한 근간과 함께 CFB 소개<br/><br/><br/>

### 3.1 Context of Use

- **CFB(the Content Flow Bar)는 누구나 온라인 공개 교육 자료를 볼 수 있도록 설계된 교육 플랫폼 2에 배치**<br/><br/>

- 의도된 기능 중 하나<br/>
: 학습자와 교육자가 자체 커리큘럼을 구성하는 것.<br/>

   - [예시] = 공개 교육 자료를 검색하고 내용의 잠재적 관련성을 판단하는 것.<br/>

   - 학습자와 교육자 모두를 위해 설계되었지만, **여기서는 후자 그룹에 대한 유용성과 유용성을 평가.** <br/><br/>

- **플랫폼**은 검색 도구, CFB 및 계단식 메뉴와 함께 **그림 1에서 볼 수 있음.** <br/>
   - 이 스크린샷은 **사용자가 플랫폼에 가입**하여 **'기계 학습'이라는 주제를 검색할 때 무엇을 볼 수 있는지 보여줌.**<br/><br/>

- 시스템이 반환하는 결과 비디오는 축소판 보기로 표시.<br/><br/>

- CFB는 각 비디오에 통합되어 있어 시간에 따라 다룬 (위키피디아) 주제를 비디오로 시각화하고 쿼리와 관련하여 각 비디오의 가장 관련성이 높은 부분을 강조 표시.<br/><br/>

- CFB에는 위키백과 개념에 대한 정의도 포함되어 있어 사용자가 이 용어를 잘 모를 경우 접근 가능함.<br/><br/>

- 직관적인 사용을 위해, 우리의 디자인은 익숙한 UX 패턴과 기술을 활용하는데, 주로 팝업, 컬러 코딩 위젯 및 계단식 메뉴를 사용.<br/>
   - 이 플랫폼에는 CFB와 함께 사용하도록 설계된 다른 통합 기능/도구도 포함됨.<br/><br/>

- 이러한 것들은 [6, 29]에 설명되며 학습 경험을 지원하는 것을 목표로 함.(예: 학습 경로의 최적화, 비디오의 주석, 추천 시스템 [8, 9 등).<br/><br/>

![그림2](https://user-images.githubusercontent.com/100738522/199810744-55e0586f-75be-4f96-9185-f4feaac2922d.png)

**[그림2] 연구의 스크린샷, 중요한 구성 요소 강조 왼쪽 하위 그림은 결과 화면**<br/>
- 각 작업에 대해 비디오 표시 
- 오른쪽에는 비디오를 클릭하면 열리는 비디오 플레이어 화면(팝업) 표시<br/><br/><br/>


### 3.2 Content Flow Bar (CFB)

#### [ CFB 사용 ]

- (다른 비디오 조각에 대해 나타나는) **비디오 콘텐츠의 의미론적 'snippets' 제공** <br/>
   - 동영상 클릭 시, 새 페이지를 여는 대신 동영상 플레이어를 표시하는 데 팝업이 사용되었음. ( [그림2]의 오른쪽 하위 그림 참조 ) <br/><br/>
   
- **계단식 메뉴( [그림1]의 녹색 사각형으로 강조 표시 )는 특정 타임스탬프에 있는 비디오의 키워드 표시** <br/>
   - 사용자는 콘텐츠를 클릭하지 않고 비디오에 포함된 주제 탐색 가능 ! <br/><br/>
   
 - **CFB의 일부로서 키워드의 정의도 팝업 형태로 제공** <br/>
   - 참고 : 이러한 키워드와 정의는 (추후 설명하는) 위키화 프로세스에서 자동으로 추출되었음. <br/><br/>
   
 - **쿼리에 대한 각 조각의 예측 관련성을 나타내는 다른 색상 강도(노란색, [그림 1] 참조)를 사용하여 추가로 지원** <br/>
  ( = 친숙한 시각적 인터페이스 요소 결합) <br/>
   - 이는 사용자가 미리 보기 행렬을 빠르게 훑어보고 가장 적절한 것을 선택할 수 있도록 하기 위함. <br/><br/>
 
#### [ CFB에 (전반적으로) 사용되는 큐잉의 유형의 역할 ]
- 사용자는 비디오 강의에서 다루는 내용을 한 눈에 확인하고, 특정 지점에서 멈추고 더 많은 내용을 발견할 수 있음. <br/><br/>

- 참가자는 메인 창에서 비디오 조각을 더 자세히 보고 싶을 때 해당 조각을 바로 이동 가능함. <br/>
   - 그러면 비디오 플레이어 창이 열리고, 이 특정 조각에서 비디오가 시작됨. <br/><br/>
   - 모든 참가자는 비디오 타임라인을 따라 커서를 이동하여 비디오 탐색 가능함. <br/><br/><br/>


### 3.3 Wikification to Extract Keywords

#### [ 키워드를 추출하는 위키화 ]

- 우리의 도구 (CFB)는 TransLectures 프로젝트3의 전사 및 번역 알고리즘을 사용하여 비디오의 텍스트 표현을 얻음. <br/><br/>

① 위키화 프로세스에서, 자원의 영어 텍스트 표현(필요할 때 번역)은 긴 문서를 약 500자 (비디오에서 약 5분)의 단편으로 분할하는 데 사용됨.[9]<br/>
   - why? 이전 작업이 그러한 단편화가 적절하다고 판단하기 때문 <br/><br/>

② 그런 다음 각 조각은 자연어 처리 엔티티 연결 방법을 사용<br/>
   - 관련성이 있고 두드러진 위키백과 개념으로 텍스트를 레이블링하는 openWikifier 서비스4를 사용하면<br/>
   - 자동으로 주석을 달 수 있음. [4]<br/><br/>

#### [ 결론 ] <br/>
   - 우리의 접근 방식은 도메인에 구애받지 않고, <br/><br/>
   - 가장 크고 끊임없이 진화하는 지식 기반인 위키피디아를 활용하여 값비싼 전문가 레이블링의 필요성을 피하는 동시에, <br/><br/>
   - 여러 언어로 작업하고 설명과 정밀 조사를 가능하게 하는 인간적으로 해석 가능한 주석을 허용함[3].<br/><br/><br/>

#### [ 참조 ]
   - 엔티티 연결 태스크에 대한 성능을 포함한 위키화의 자세한 내용은 [4]를 참조.<br/><br/><br/>
 
---
## 4. User Evaluation

#### [ 사용자 연구 수행 ]

- 도구를 설계하는 동안 **CFB가 있는 것과 없는 두 가지 버전의 정보 검색 작업**을 받은 **8명의 참가자를 대상**으로 **예비 사용자 연구(실제 연구 이전)를 수행** <br/><br/>

- **정성적 피드백** <br/>
   - 모든 참가자들이 **도구가 흥미롭고 직관적이며 비디오에서 정보를 찾는 데 도움이 된다**는 것을 보여줌.<br/>
   - 특히 **콘텐츠를 알 수 없는 긴 영상으로 장점이 두드러짐.**<br/><br/>

- **결론** <br/>
   - **CFB를 통해** 참가자는 **"실제로 관심 있는 부분으로 건너뛸 수 있기 때문에"** 작업이 더 쉽고 더 즐겁다는 것을 알게됨.<br/><br/><br/>


### 4.1 Controlled User Study <br/><br/>

- **정보 검색 및 수집을 위한 CFB의 효과를 평가**하기 위해 26명의 참가자를 대상으로 사용자 연구를 수행 <br/><br/><br/>

### 4.2 Goal of Study and Research Questions


#### [ 사용자 연구 ]

- 주요 사용자 연구는 CFB(제어 조건)가 있는 비디오 플레이어의 사용자 성능을 비교하기 위해 설계됨.<br/>
   - 제어 비디오 플레이어는 유튜브를 기반으로 호버링할 때 변화하는 섬네일을 보여주고 시청된 부분을 강조 표시(그림 3 참조). <br/><br/>

- 향상된 비디오 플레이어는 CFB를 가지고 있었는데, 여기에는 각 단편에서 다루는 주제 목록과 그 정의(그림 2 참조)가 포함.<br/><br/>

- 이 비교 접근법은 비디오 플레이어 상호 작용을 평가할 때 사용되는 일반적인 방법 [22, 37]<br/><br/>

- 기계 학습과 기후 변화와 관련된 두 가지 과제를 설계<br/><br/>

   - 기계 학습은 학문적으로 인기 있는 주제이기 때문에 선택<br/>
   - 기후 변화는 보편적인 관심사 때문에 선택<br/>
   - 이 두 가지 모두가 주제이며, CFB가 통합된 플랫폼에서 사용할 수 있는 많은 비디오가 있음.<br/><br/>

   - 기계 학습, 기후 변화 과제 둘 다 참가자들이 각 도메인을 가르치는 데 유용한 관련 동영상을 찾도록 지시받은 정보 찾기 작업임.<br/><br/>

- 정보 작업을 선택한 이유?<br/>
   - 정보 작업이 더 어렵고 시간이 많이 걸리는 경향이 있기 때문에 탐색 작업보다 정보 작업을 선택함.<br/><br/><br/>

#### [ 사용자 연구 목적 ]

- CFB가 정보 찾기 지원 여부와 방법을 파악하여, 콘텐츠 탐색을 촉진하고 비디오 콘텐츠의 효율적인 브라우징을 지원하는 데 있음. <br/><br/>

#### [ 본 연구를 위한 주요 연구 질문 (2가지) ]

① 내비게이션과 브라우징은 두 인터페이스에서 어떻게 비교됩니까? <br/><br/>
② 정보 추구와 탐색적 행동의 측면에서 어떤 차이가 있습니까? <br/><br/><br/>

### 4.2.1 사용자 조치

- 연구 질문에 답하기 위해, 다음과 같은 다섯 가지 조치에 초점을 맞추어 성능과 사용자 경험의 특정 측면에 특히 주의를 기울임.<br/><br/>

- 초점 (5가지)<br/><br/>

1) 동영상 열기, 즉 참가자가 동영상을 클릭하기로 결정했을 때 비디오 플레이어 화면이 열림 <br/>
2) 비디오 플레이어 화면에서 비디오 재생/재생 <br/>
3) 비디오 탐색(결과 화면 또는 비디오 플레이어 화면에서) CFB의 키워드 또는 축소판 그림 프레임과 같은 비디오의 내용을 탐색하는 것<br/>

4) 관련 비디오 세그먼트의 선택, 즉, 사용자가 비디오의 일부가 당면한 작업과 관련이 있다고 판단하고 작업 공간에 관련 세그먼트를 저장하는 경우 및 <br/>
5) 비디오 내에서 찾는 정보 [14], 즉, 검색 작업은 사용자가 비디오 내에서 탐색하는 경우(재생할 비디오의 여러 시간 위치에서 이동/이동)<br/><br/>

- 비디오의 일부를 열고 재생하고 선택하는 동작은 두 조건(CFB ON/OFF)에서 동일합니다. <br/>
   - 그러나 탐색은 다르다. <br/><br/><br/>


#### [ 두 경우 (CFB ON/OFF) 모두 비디오 아래의 시계열 표시줄(결과 및 비디오 플레이어 화면에 모두 있음)과 상호 작용하여 콘텐츠를 탐색 ]

**① CFB가 꺼져 있을 때** <br/><br/>

- 탐색 경험은 유튜브의 주류 비디오 플레이어와 유사하게 유지<br/><br/>
- 결과 화면<br/>
   - 시계열 막대 위를 맴돌면 마우스 커서에 해당하는 비디오의 시간 위치가 표시<br/>
   - 시간 위치에 대응하는 프레임들을 미리 보는 비디오 섬네일이 디스플레이 됨.<br/><br/>

- 비디오 화면<br/>
   - 축소 이미지 표시가 비활성화되어 있는 동안 시간 위치가 유지<br/>
   - 비디오에서 본 부분은 빨간색으로 표시되어 있음.<br/><br/>

- [그림 3]은 CFB가 꺼졌을 때의 비디오 플레이어 <br/><br/>


**② CFB가 켜져 있는 경우**<br/><br/>

- CFB 꺼짐 상태와의 유일한 차이점<br/>
   - 시간이 (위키백과 키워드와 정의가 있는) CFB 팝업으로 대체된다는 점<br/><br/>

- CFB 꺼짐 상태와의 유사점 ( in 축소판 미리 보기)<br/>
   - 결과 화면 : 활성화<br/>
   - 비디오 화면 : 비활성화<br/><br/><br/>

![그림3](https://user-images.githubusercontent.com/100738522/199811141-773b05cd-76af-4021-9030-954860446695.png) <br/><br/>
**[그림3] CFB가 꺼진 비디오 플레이어** <br/>
- 타임라인의 커서 : 시간 위치 <br/>
- 빨간색 대시와 점 : 감시된 부품<br/><br/><br/>



### 4.3 Experimental Design and Procedure

이 연구는 반복 측정 설계를 사용했기 때문에, 각 참가자는 CFB와 통제 조건을 사용하여 두 가지 작업을 모두 수행하며, 훈련 효과와 피로를 해결하기 위해 이들 간에 균형을 맞춘다. 

이는 참가자들이 두 가지 조건과 과제를 제시한 순서가 무작위로 결정되었음을 의미한다. 

CFB 조건은 연습 과제에서 입증되었다.

연구 전에 참가자들은 세션 전에 서명하기 위한 정보 시트와 동의서를 받았습니다. 

이 연구는 줌 웹 회의 플랫폼을 통해 이루어졌다. 연구원은 먼저 참가자들에게 인구 통계학적 질문을 하는 초기 양식을 제공하고 기후 변화와 기계 학습 모두에 대한 지식을 평가했습니다.

두 작업의 주제에 대한 지식 그런 다음, 연구자는 연구에 필요한 기능(CFB ON/OFF 포함)을 강조하면서 연구에 대한 간략한 개요를 제공하고 플랫폼을 데모했다.
그런 다음 참가자들은 본 연구로 넘어갈 수 있다는 확신을 가질 때까지 "두뇌"라는 주제에 대해 두 가지 조건을 모두 가지고 연습했습니다.

그런 다음, 각 참가자는 두 주제 모두에 대한 정보 탐색 과제를 수행했다(과제 순서 무작위화). 

앞에서 설명한 바와 같이, 개방형 환경에서 CFB의 사용을 탐구하기 위한 시간 제약이 주어지지 않았다. 

그 후 그들은 CFB에 대한 설문지를 작성하도록 요청받았다. 

정보 수집 작업으로서, 사용자가 여러 작업에 걸쳐 지식 영역에 익숙해진다면, 이는 포착되고 분석되는 상호 작용 행동에 영향을 미칠 것이다. 

분석을 혼란스럽게 할 수 있는 이러한 학습 효과를 피하기 위해 사용자에게 세 가지 작업(실습, 작업 1 및 작업 2)에 세 가지 다른 주제(뇌, 기후 변화 및 기계 학습)가 사용된다.
그림 2는 사용자 연구의 요약을 보여줍니다. 각 과제(기계 학습 및 기후 변화)에 대해, 참가자들은 연구를 위해 신중하게 선택된 18개의 비디오와 함께 결과 화면에 제시되었다. 

그림 2(왼쪽)에 표시된 비디오 결과 집합은 무작위로 순위가 매겨졌습니다. 즉, 비디오는 작업 주제와의 관련성과 무관하게 정렬되었습니다.

그러나 모든 비디오는 작업 해결과 관련이 있도록 선택되었습니다. 

이 순위는 각 참가자가 동일한 순서로 비디오를 볼 수 있도록 모든 참가자들 사이에서 일정하게 유지되었습니다. 

베이스라인 비디오 플레이어는 YouTube를 기반으로, 맴돌 때 변화하는 섬네일을 보여주며, 시청한 부분을 빨간색 점으로 강조 표시했다. 

향상된 비디오 플레이어는 CFB를 가지고 있었는데, 여기에는 각 단편에서 다루는 주제 목록과 그 정의들이 포함되어 있다. 

사용자 연구가 정적 결과 집합으로 제한됨에 따라(사용자 쿼리 기반 동적 결과 집합과는 달리), 그림 2에 있는 사용자 연구 인터페이스에서 CFB의 관련성 기반 단편 강조 기능이 비활성화되었다.

 참가자가 비디오를 클릭하면 비디오 플레이어가 열리고 참가자가 비디오 플레이어 화면으로 이동합니다(그림 2 참조). 참가자들에게는 비디오 클립을 선택하고 작업 공간에 저장할 수 있는 기능도 제공되었다. 

참가자가 비디오 클립을 선택하면 선택한 세그먼트가 CFB에서 파란색으로 강조 표시되고 비디오 제목이 참가자의 작업 영역에 표시됩니다. 
또한 참가자는 작업영역에서 선택 항목을 삭제할 수 있습니다.
과제. 참가자들에게 두 과제를 완료하기 위해 다음과 같은 가상의 시나리오를 제시하였다. 과제 1(기후 변화): "기후 변화에 관심이 있으시니까, 한 친구가 기후 변화에 대한 데이터 과학의 적용을 보여주는 흥미로운 비디오 클립 2개를 찾아달라고 부탁했습니다. 

그 후에, 여러분의 친구는 기후 변화의 논쟁적인 문제들을 설명하는 비디오 클립 2개를 찾기를 원합니다. 

이 비디오 클립들은 수업시간에 토론을 시작하는 역할을 할 것이다. 비디오를 보는 데 시간이 너무 오래 걸리지 않기 때문에, 학생들이 볼 수 있도록 최소 4개의 짧은 비디오 클립이나 세그먼트(예: 5-6분)를 선택해야 합니다. 

비디오당 비디오 클립/세그먼트를 두 개 이상 선택하지 마십시오." 과제 2(기계 학습): "몇몇 학생들은 다음 워크숍에서 기계 학습에 대해 배우고 싶어합니다. 

그것의 중요성이 커짐에 따라, 여러분은 학생들이 집에서 볼 수 있고 메모할 수 있는 주요 개념을 설명하는 비디오 클립을 찾는 일을 맡게 됩니다. 

그런 다음 워크숍에서 기계 학습 응용 프로그램에 대한 비디오 클립 2개를 보여주고 그들과 논의하기를 원할 것이다. 

비디오를 보는 데 시간이 너무 오래 걸리지 않기 때문에, 학생들이 볼 수 있는 최소 4개의 짧은 비디오 클립 또는 세그먼트를 선택해야 합니다(예: 5-6분). 
비디오당 비디오 클립/세그먼트를 두 개 이상 선택하지 마십시오."
동영상. 연구를 위해 선택한 모든 동영상은 플랫폼에서 찾을 수 있으며 저장소 VideoLectures.net에 속해 있습니다. 

우리는 각 과목에서 18개의 교육 영상을 선별했다. 모든 비디오는 학술 컨퍼런스 프레젠테이션(또는 전문 세미나 및 여름 학교)에서 가져온 것입니다. 

대부분의 경우, 강연자의 파워포인트 프레젠테이션이 캡처되어 비디오에 포함되어 있습니다. 우리는 선택된 비디오 세트가 주어진 과제를 달성할 수 있는지 확인했다.
설문지. 우리는 툴에 대한 사용자 경험을 이해하기 위해 CFB의 특정 측면에 대한 설문지를 개발했다. 

설문지에는 시스템 사용적합성 척도에서 영감을 얻은 개방형 질문과 등급이 모두 포함되어 있다[21]. 그 설문지는 인구통계학과 교수 경험에 대한 질문으로 시작되었다. 

또한 참가자들에게 각 주제에 대한 지식을 직접 보고하도록 요청했습니다. 

인구통계학 및 지식과 관련된 설문지의 이 부분은 참가자가 도구와 상호 작용하기 전에 수행되었다. CFB와 관련된 질문이 포함된 설문지의 두 번째 부분은 참가자들이 연구에 참여한 후에 질문되었다. 

설문지의 두 번째 부분에서 참가자들에게 먼저 CFB에 대한 진술의 등급을 매긴 다음, 엔티티 링크에 의해 생성되고 CFB에서 사용되는 주제의 적절성을 보다 구체적으로 평가하도록 했다. 

일부 참가자들에게 점수를 매기도록 요청했습니다. i) 향상된 비디오 플레이어는 사용하기 직관적입니다. ii) 향상된 비디오 플레이어는 비디오 클립을 더 쉽게 찾을 수 있게 해 줍니다. iii) CFB로 정보를 찾는 것이 어렵다는 것을 알았습니다. iv) 주제에 대한 정의를 제공하는 것이 도움이 되었습니다. v) 더 많은 비디오 플레이어가 CFB를 포함해야 합니다. 우리는 강하게 동의하지 않는 것부터 강하게 동의하는 것까지 6개 항목의 Likert 척도를 사용했습니다. 

마지막으로, 참가자들은 CFB, 사용자 연구 및 생성된 키워드에 대한 경험을 자세히 설명하도록 요청받았다. 

결론적으로, 참가자들에게 연구, 도구 또는 작업과 관련된 추가 의견이 있는지 물었다. 

사용된 설문지 사본은 보충 자료와 함께 첨부된다.
정성 분석. 

우리는 연구의 개방형 질문과 인터뷰 기록의 답변을 사용하여 귀납적 주제 분석을 수행했다. 

주제 분석의 목표는 CFB에 대한 참가자들의 경험, 인식 및 반응을 더 잘 이해하는 것이다. 

우리는 Braun과 Clarke에 의해 요약된 주제 분석의 원칙에 따라 데이터를 코딩했다. 

우리는 코드를 코딩하고 검토하고 범주로 그룹화한 다음 주제를 정의하는 등 이 방법에 내재된 주요 단계를 따랐다. 각 단계에서 우리는 분석에서 새로운 패턴이 이용 가능한 데이터로부터 나오고 참가자들의 경험을 반영하도록 노력했습니다.

### 4.4 Participants

26명의 참가자들이 이 연구에 참여했습니다. 대부분의 참가자들은 30세에서 39세 사이였습니다. 그들은 모두 i) University College London 및 ii)의 컴퓨터 과학부의 직원(박사 학생, 포스트 닥터 및 교수진)이었다. 오픈 대학교 (영국). 그들은 모두 교사 경험이 있고 컴퓨터에 능통했다. 

남성(53.6%)이 여성(46.4%)보다 약간 많았다. 기계 학습과 기후 변화라는 두 가지 주제에 대한 그들의 지식은 다양했다. 

대부분의 참가자들은 기계 학습에 대한 평균 이상의 지식을 가지고 있으며, 40%는 기계 학습에 대한 전문 지식을 가지고 있다고 보고했다. 

대조적으로, 참가자의 50%는 거의 지식이 없었고, 나머지는 대부분 기후 변화에 대한 평균적인 지식을 가지고 있었다.

사전 지식을 위해 명시적으로 테스트하지는 않았지만(오히려 자체 보고가 허용됨), 모든 참가자는 컴퓨터 과학 부서에서 왔으므로 적어도 기계 학습에 대한 기본적인 지식을 가질 것으로 예상된다.

### 4.5 Click Stream and Interaction Log Analysis

클릭 및 관련 사용자 인터페이스 구성 요소와의 기타 상호 작용(예: 개체 위로 맴돌기, 팝업 트리거 및 닫기 등)과 관련된 높은 세부 사용자 상호 작용 로그를 캡처하기 위해 사용자 인터페이스 내에 추가 프로그래밍 스니펫을 구현했다[24]. 

기록된 사용 로그는 서로 다른 상호 작용 메트릭을 계산하여 상호 작용 패턴을 추론하기 위해 후처리됩니다[18]. 4.5.1상호 작용 메트릭입니다. 

우리는 시간 [2, 33], 활동 [24, 33], 위치 [2, 41] 및 비디오 세그먼트 선택을 기반으로 여러 범주로 그룹화될 수 있는 IR 시스템의 사용자 행동을 측정하는 데 사용되는 다양한 상호 작용 메트릭을 계산한다. 

CFB는 주로 비디오의 주제 콘텐츠를 미리 볼 수 있는 기회를 소개하기 때문에, 비디오에서 주제를 탐색하는 사용자와 관련된 활동을 포착하는 데 더 중점을 둔다. 

CFB를 포함하거나 포함하지 않고 분석한 상호 작용 메트릭 범주는 다음과 같습니다. 시간을. 

우리는 참가자들이 다른 행동에 소비한 시간과 관련된 일련의 상호 작용 메트릭을 계산했다. 

우리가 분석한 측정 기준은 i) 연구의 작업을 완료하는 데 소요된 시간, ii) 결과 화면에 소요된 시간, iii) 작업 중에 비디오를 보는 데 소요된 시간, iv) 결과 화면에서 비디오의 내용을 탐색하는 데 소요된 시간, vi) v의 내용을 탐색하는 데 소요된 시간이었다.비디오 플레이어 화면의 아이디어, vii) 열린 비디오당 비디오를 보는 데 소비한 시간 및 vii) 탐색된 비디오당 비디오의 내용을 탐색하는 데 소비한 시간. 

비디오 콘텐츠 탐색을 고려할 때, 우리는 시계열 막대를 맴도는 데 걸린 시간을 측정했다(섹션 4.2.1 참조).
활동. 다양한 활동 패턴을 분석하기 위해 빈도 및 비율 기반 메트릭에 해당하는 7가지 상호 작용 메트릭을 측정했습니다. 

이러한 메트릭은 다음과 같습니다. i) 열림/재생된 고유 비디오 수, ii) 재생된 고유 비디오당 재생 세션 수(즉, (i)/(ii) 재생된 비디오 수, iv) 선택 후 1분 이내에 제거된 세그먼트 수, v) 제거된 세그먼트 수, vi) 전체 작업 시간의 일부로 결과 화면에서 탐색하는 데 소요된 시간 및 vi.i) 전체 작업 시간의 일부로서 비디오 플레이어 화면에서 탐색하는 데 소요된 시간.

네비게이션. 우리는 참가자가 시스템 내에서 탐색하는 위치에 대한 단서를 제공하는 몇 가지 메트릭을 계산했다. 

여기에는 i) 전체 작업을 통한 탐색 동작의 수(사용자가 재생하기 위해 비디오의 다른 시간 위치로 점프하는 경우), ii) 열린 비디오당 비디오 내의 탐색 동작의 수, iii) 재생된 비디오의 가장 깊은 순위(즉, 열린 비디오 목록의 최대 순위), iv) 탐색된 비디오의 가장 깊은 순위(즉, e.이전 측정 기준과 유사하지만 탐색한 비디오의 경우) 및 v) 비디오 내에서 탐색된 위치(즉, [0,1]에서 정규화된 비디오의 평균 위치)를 의미한다. 가장 깊은 순위는 사용자가 결과 화면에서 하위 순위의 결과를 고려하도록 권장했는지에 대한 통찰력을 주었다. 수치가 클수록 순위가 낮은 항목에 사용자의 관심이 집중되었음을 나타낸다.

선택. 
우리는 작업과 관련된 것으로 선택된 참가자와 관련된 몇 가지 추가 메트릭을 계산했다. 

i) 첫 번째 선택 전에 걸린 시간, ii) 첫 번째 세그먼트를 선택하기 전에 열어서 재생한 비디오 수, iii) 첫 번째 세그먼트를 선택하기 전에 탐색한 비디오 수 및 iv) 선택한 세그먼트의 평균 지속 시간입니다.

### 4.6 Statistical Analysis

사용자 연구의 목표 중 하나는 두 조건(CFB on vs. off)에 대한 상호작용 메트릭을 객관적으로 비교하여 두 그룹의 분포가 통계적으로 다른지 확인하는 것이다.

웹 기반 문서와 상호 작용한 많은 지표(예: 비디오 시청 시간 [7], 클릭으로 체류 시간 [38])는 비정규 분포를 따르는 경향이 있으며, 대신 비모수 가설 테스트의 사용에 동기를 부여한다[18]. 

측정의 비정규성으로 인해 Wilcoxon 부호 순위 검정 [13]을 사용하여 두 조건 간의 값 차이를 비교했습니다.

4.3절에 따라 학습 효과를 피하기 위해 두 가지 조건에 대해 매우 다른 두 가지 지식 영역(기후 변화와 기계 학습)이 사용되었습니다. 

초기 분석 결과, 두 주제 사이에 유의미한 행동 차이가 있는 것으로 나타났는데, 아마도 다른 비디오와 주제 또는 참가자의 배경 때문일 것이다(섹션 5.1과 그림 4(c) 참조). 

따라서 동일한 참가자의 두 조건을 쌍체 관측치로만 비교하는 것은 오해를 불러일으킬 수 있습니다. 

이 문제를 해결하기 위해 각 참가자의 제어 작업(CFB 꺼짐)을 동일한 주제에 대해 치료 작업(CFB on)을 수행한 무작위로 선택된 다른 참가자와 쌍으로 구성했다. 

페어링이 완료되면 새로운 페어링 관측치를 사용하여 Wilcoxon 부호 순위 테스트를 실행했습니다. 

관측치를 합성 쌍으로 구성하여 얻은 결과의 통계적 신뢰성을 보장하기 위해 무작위 쌍은 5회 반복된다. 

5명의 참가자 쌍 구성에 대해 수행된 가설 테스트 결과는 표 1에 보고된다. 5개의 페어링 구성에서 얻은 자세한 결과는 보충 자료와 함께 첨부됩니다.

---
## 5. Effect of CFB User Interaction Behaviours and Perceptions

우리는 주로 사용자 상호 작용 로그, 설문 조사 및 주제 분석을 통해 얻은 결과에 분석을 집중한다. 

표 1은 상호작용 로그에 대해 수행된 통계 분석의 결과를 나타낸다. 우리는 평균 쌍별 차이와 통계 테스트의 중요성에 대해 논평한다. 

그림 4에는 작업 간 동작의 현저한 차이를 나타내는 여러 상자 그림이 포함되어 있다. 그림 5는 설문지를 분석하여 얻은 주요 결과를 요약한 것입니다.

### 5.1 Differences Across Tasks
그림 4에는 관련 결과를 요약한 세 개의 상자 그림이 나와 있습니다. 

요약하면, 우리는 작업 주제와 작업 순서를 고려할 때 상호 작용 로그 결과에서 현저한 차이를 발견했다. 

그림 4의 하위 그림 a)와 b)는 조건에 관계없이 첫 번째 작업을 수행하는 데 걸리는 시간이 두 번째 작업을 수행하는 데 걸리는 시간(CFB ON/OFF)보다 체계적으로 더 크다는 것을 나타낸다. 

이는 연구 중에 학습 효과가 발생할 수 있음을 시사한다. 

첫 번째 과제에서 이러한 학습 효과는 참가자들이 CFB에 노출될 때 더 두드러지는 것으로 보인다. 그러나 두 번째 작업에서는 두 조건 모두 비슷한 시간이 걸리며, 경우에 따라 CFB는 더 적은 시간이 걸린다. 

이는 두 번째 작업의 전체 작업 기간이 CFB가 비활성화된 그룹의 작업 기간과 동일한 양으로 수렴되기 때문에 시각적 CFB 도구가 직관적이라는 것을 나타낼 수 있다. 

우리는 이것이 사용자가 CFB 기능을 1시간 미만으로 상호 작용함으로써 이해하고 배울 수 있다는 증거라고 믿는다. 하위 그림 c)는 사용자가 각 작업이 끝날 때 동일한 수의 세그먼트를 선택하라는 조언을 받았음에도 불구하고 작업의 주제에 따라 사용자가 선택한 세그먼트의 수가 다르다는 것을 보여준다. 

참가자가 기계 학습 주제에 더 익숙했기 때문에 이는 주제와 관련된 과제의 복잡성 차이를 나타내는 것일 수 있다. 

또한, 비록 과제가 유사하지만, 기후 변화 과제는 더 구체적이며, 참가자들에게 i) 기후 변화에 대한 데이터 과학의 적용과 ii) 기후 변화에 대한 논쟁적인 이슈를 찾아보라고 요청하는 반면, 기계 학습 과제는 주제를 이해하고 그 적용을 보여주기 위한 관련 자료를 강조하도록 요청한다..

이러한 관찰은 개별적인 두 조건을 쌍체 관찰로 사용하는 대신 작업 순서와 작업 주제가 유사한 사용자 작업을 쌍으로 구성하여 통계 분석을 수행하도록 동기를 부여했다(섹션 4.6에 요약됨).

![그림4](https://user-images.githubusercontent.com/100738522/199811359-36158c8c-409e-4c19-a81d-2d272c46b0d4.png)

**[그림4 ] 작업 순서와 주제 간의 상호 작용 행동의 차이를 나타내는 상호 작용 메트릭의 하위 집합의 상자 그림**
 
- 이러한 그림(특히 하위 그림 a와 b)은 사용자가 첫 번째 작업에 훨씬 긴 시간을 소비하는 경우 학습 효과가 발생함을 시사

- 하위 그림 c)는 사용자가 유사한 시간을 보내고 두 주제에 대해 동일한 수의 세그먼트를 선택하도록 권장되었지만, 두 가지 다른 작업에 대해 선택된 세그먼트의 수는 다르다는 것을 보임




### 5.2 Time Spent

표 1의 시간 측정 기준에서 얻은 주요 결론은 참가자들이 CFB를 사용할 때 열고 볼 콘텐츠를 선택하고 탐구하는 데 훨씬 더 많은 시간을 소비한다는 것입니다. 이는 사용자가 CFB를 사용하여 비디오 전체에서 주제 콘텐츠를 찾을 수 있음을 시사한다. 

이는 결과 화면에서 소요된 시간, 작업 중 탐색에 소요된 시간, 결과 화면에서 탐색에 소요된 시간과 같은 메트릭 테스트의 중요성에 의해 입증된다. 

이 동작은 그들이 어떤 비디오를 볼지 결정하기 위해 키워드를 사용하고 있음을 암시할 수 있다. 

이는 CFB에 사용자가 비디오 컬렉션 내에서 탐색할 수 있는 가능성이 있음을 나타낼 수 있다.

비록 그 결과가 통계적으로 유의하지는 않지만, 시간은
또한 표 1의 측정기준은 참가자가 CFB로 과제를 완료하는 데 더 적은 시간을 소비한다는 것을 보여준다. 

그들은 또한 자료를 보는 데 더 적은 시간을 보낸다. 

마지막으로, 결과는 참가자들이 특정 비디오 내의 콘텐츠를 탐색하는 데 더 많은 시간을 보낸다는 것을 보여준다.

### 5.3 Users Activity

활동 그룹은 참가자들이 과제를 완료하는 동안 대부분의 시간을 결과 화면에서 비디오를 탐색하는 데 보낸다는 것을 다시 보여줍니다. 

통계적으로 유의하지는 않지만 비디오 플레이어 화면에서 탐색하는 데 더 많은 시간을 소비합니다. 

그러나, 그들은 평균적으로 비디오를 덜 보고, 재생되는 독특한 비디오당 재생 세션도 더 적게 한다.

 이것은 그들이 더 낫거나 더 빠른 관련성 판단을 할 수 있음을 나타낼 수 있다. 

CFB를 사용할 경우 선택 후 1분 이내에(및 스터디 전체에서) 제거된 세그먼트의 수도 더 적습니다. 

이러한 동작은 사용자가 결정을 되돌릴 때 정보 검색에서 "퀵백" 동작과 유사하며, 일반적으로 실수 동작으로 인해 발생합니다. 

이는 CFB가 관련 섹션을 선택하는 측면에서 실수가 적다는 것을 시사한다.

### 5.4 Users Navigation

표 1의 탐색 메트릭은 CFB를 통해 사용자가 결과 집합에서 더 깊이 탐색할 수 있음을 강하게 나타낸다. 

이 증거는 순위 알고리즘이 완벽하지 않을 수 있는 시스템에서도 사용자를 지원하는 이 사용자 인터페이스 구성요소의 유용성을 보여준다. 

통계적으로 중요한 것은 아니지만, 가장 깊은 재생되는 비디오의 순위는 CFB가 더 적다. 

이는 참가자들이 CFB와 함께 결과 집합의 초기 단계에서 관련성의 증거를 발견했을 수 있음을 시사할 수 있다. 

또한 표 1은 사용자가 수행하는 탐색 조치의 수가 CFB에서 더 적다는 것을 보여준다. 

이는 이 도구가 사용자가 비디오 내에서 탐색할 수 있는 권한을 부여한다는 것을 시사한다. 

그러나 결과 화면에서 볼 수 있는 것만큼 효과가 강하지는 않습니다. 

이러한 결과는 참가자가 CFB를 사용하여 더 많은 비디오를 탐색하지만 (이전 하위 섹션의 결론에 의해 제안되었듯이) 해당 비디오의 주제 내용을 확인하는 데 더 많은 시간을 소비한다는 가설을 제시한다.

하지만, 일단 그들이 자료를 공개하기로 결정하면, 그들은 어디로 갈지 더 잘 결정할 수 있고, 비디오 내에서 덜 추구할 필요가 있다. 

이것은 또한 비디오 내에서 재생되는 평균적인 위치에서도 입증되는데, CFB를 사용하는 참가자들이 평균적으로 더 적은 자료를 시청하더라도 비디오에서 더 깊은 플레이를 한다는 것을 보여준다.

### 5.5 Selecting Relevant Content

표 1의 선택 지표는 CFB를 사용하는 참가자가 작업에 대한 첫 번째 관련 비디오 세그먼트를 선택하기 전에 더 적은 수의 비디오를 재생한다는 것을 나타낸다. 

평균적으로, 참가자들은 관련성 판단을 내리기 전에 비디오를 탐색하는 횟수가 적으며 비디오의 관련 세그먼트를 선택하기 전에 소비하는 시간도 적습니다. 

또한, 선택된 세그먼트의 평균 지속 시간은 CFB를 가진 참가자들이 더 적은 콘텐츠를 선택한다는 것을 보여준다. 우리는 이것이 그들이 훨씬 더 세분화된 세그먼트를 선택할 수 있기 때문이라고 믿는다.

### 5.6 Users Perception of the CFB

설문 조사. 

설문지 등급 척도에서 대부분의 참가자가 CFB에 대해 긍정적인 반응을 보였다는 것을 알 수 있다(82%가 비디오 클립을 더 쉽게 찾을 수 있다고 동의했다). 

대다수는 CFB를 즐겨 사용한다는 점과 직관적이라는 점(75%)에 동의했습니다. 

참가자들이 일부 키워드의 적절성에 대해 보고한 몇 가지 문제에도 불구하고, 참가자들은 CFB에 만족하는 것처럼 보였다. 거의 93%가 더 많은 비디오 플레이어가 CFB를 포함해야 한다는 데 동의했다.

![표1](https://user-images.githubusercontent.com/100738522/199902349-7c1715e5-52e3-4803-ae51-6258daacfb6c.png) <br/>
**[표1] 5개의 무작위 사용자 쌍 구성에 대해 수행된 평균 및 통계 분석(CFB 꺼짐과 CFB 켜짐의 쌍별 차이)과 함께 제시된 사용자 연구 동안 기록된 상호 작용 로그를 사용하여 계산된 다양한 메트릭**

- 통계적으로 유의한 쌍들의 차이는 h 𝑝 < 0.01 as (∗∗∗), 𝑝 < 0.05 as (∗∗) and 𝑝 < 0.10 as (∗)와 같이 표시된다. 

![그림5](https://user-images.githubusercontent.com/100738522/199811458-2b684895-b266-4b53-90fb-52e100643e01.png) <br/>

**[그림5] 선택한 질문에 대한 응답**
- 사용자 설문지 6등급 Likert 척도 사용
- 다른 색조의 파란색이 동의 응답에 사용
- 다른 색조의 보라색은 동의하지 않는 응답에 사용

주제 분석. 
주제분석을 이용하여 설문지의 개방형 질문에 대한 반응을 분석해보니 두 가지 주요 주제가 나타났다. 

이것들은 i) 비디오 콘텐츠 탐색과 ii) 긍정적인 사용자 경험이었다. 

우리는 이제 참가자들의 진술 중 일부를 포함함으로써 이것들을 입증한다. 

사용자 설문 조사 결과와 유사하게, 참가자들은 도구에 대해 긍정적인 반응을 보였는데, 한 참가자는 "나는 그 기능이 정말 마음에 든다, 나는 그것을 자주 사용할 것이다"라고 말했다. 

또한 CFB는 사용자에게 유용하고 사용하기 쉬워 보였다. "일단 몇 분 안에 설명하면 대부분의 사람들에게 사용법이 아주 분명해질 것입니다." "전반적으로, 플로우바는 검색에 훨씬 더 집중된 느낌을 주었습니다." "여러 용어 위에 맴돌면 많은 용어들이 그 용어에 대한 설명이 있다는 것은 정말 도움이 된다." 

CFB(특히 긴 영상에서) 없이 동영상을 선택하려는 일부 참가자들의 반응이 주목된다.
 
"일단 기계 학습에 들어갔을 때, 당신이 클립 4개를 찾으라고 했을 때... urg" 

특히, 참가자들은 CFB 없이 클립을 선택하는데 필요한 노력에 실망한 듯 보였다: "확실히, 나는 처음에 키워드 없는 표준 비디오 플레이어로 꽤 좌절했다는 것을 본 것 같다. 

대부분의 참가자들은 개방형 질문에서 비디오 콘텐츠를 탐색하는 것과 관련하여 CFB의 몇 가지 이점을 강조했는데, 이는 i) 비디오 탐색 및 정보 위치 확인 향상, ii) 비디오의 개요를 얻는 것으로 요약할 수 있다.

참가자들은 긴 비디오에 특히 중요한 비디오를 더 쉽게 스크롤하고 훑어볼 수 있었다. "특히 긴 비디오의 경우 비디오의 내용을 건너뛰는 데 도움이 됩니다." 

그들은 정보를 더 빨리 찾을 수 있었고 그것은 그들이 보고 싶은 비디오의 어떤 부분을 직접 선택할 수 있게 해주었다. "정해진 시간이 있다면 더 많은 양의 자료를 처리할 수 있습니다."
참가자들은 먼저 썸네일과 비디오 제목을 살펴본 다음 CFB 키워드를 사용하여 보고 싶은 비디오 세그먼트를 직접 선택할 수 있습니다. 

"저는 비디오를 무작위로 클릭하는 것보다 섹션부터 바로 앞으로 쓸어갑니다." 

참가자가 관련이 있어 보이는 부분을 직접 찾을 수 없는 경우 CFB는 검색 범위를 좁히고 정보를 제거하는 데 도움을 주었다. 

"그것은 말하는 대상의 세부 사항을 식별하는 것을 훨씬 더 쉽게 만들었습니다; 그것은 화자가 대화의 흐름에서 어디에 있는지 어느 정도 느끼게 해주었습니다." 

"CFB는 비디오에서 시작 지점을 찾는 데 도움이 되며, 실제로 관련 콘텐츠를 찾는 데 항상 도움이 되는 것은 아니지만 적어도 신속하게 진행할 수 있습니다." 

CFB는 참가자들이 비디오 콘텐츠에 대한 개요를 얻고 비디오에 대한 이해를 높일 수 있도록 했다. 

"그것은 그 비디오에 대한 나의 지식을 증가시켰다. 그것은 참가자들에게 각 비디오의 요약과 다른 비디오 섹션에 대한 빠른 요약을 주었다. 

그것은 그들에게 제시된 아이디어에 대한 맥락을 제공해, 그들이 비디오의 흐름을 훨씬 더 잘 이해할 수 있게 해준다. 

"이러한 키워드는 아이디어가 무엇에 관한 것인지 요약하고 차별화하는 데 도움이 될 수 있습니다.
참가자들의 CFB에 대한 긍정적인 반응에도 불구하고, 그들은 또한
몇 가지 문제에 주목했습니다. 

부적절하거나 잘못된 키워드가 몇 개 생성되었습니다. 

대부분의 참가자들은 그것들을 무시한 것처럼 보이지만, 몇몇 참가자들은 그들이 눈에 띄게 문맥을 벗어나거나 일치하지 않을 때 어리둥절했다. 

일부 참가자들은 키워드를 넘나드는 반복이 많아 키워드가 덜 두드러지게 나타난다고 강조했다. 

"일부 동영상의 경우 키워드가 여러 세그먼트에 대해 동일하여 구별하기 어려웠다." 

특히 몇 개의 동영상에 대해서는 동영상 전반에 걸쳐 체계적으로 키워드가 반복됐다. 

참가자가 지적했듯이 그러한 키워드는 생략되어야 하며 전체 비디오에 대한 메타 태그로 포함되어야 한다. 

그러나, 참여자들의 반응은 위키화가 때때로 오류가 발생함에도 불구하고 비디오 간 및 비디오 내의 탐색을 개선한다는 확신을 주었다. 

이것은 그러한 콘텐츠 탐색 도구들을 위한 자동적이고 확장 가능한 엔티티 링크의 효용성에 대한 뒷받침되는 증거가 될 수 있다.


---
## 6. Discussion and Conclusions

우리는 콘텐츠 흐름 막대(CFB)에 대한 설계 이론적 근거와 발견 가능성 및 탐색 지원을 위한 이 새로운 상호 작용 기법의 효과를 설명하는 사용자 연구의 분석을 제시하였다. 

전반적으로 CFB는 비디오 세트에 걸쳐 초기 탐색 행동과 정보 탐색을 향상시키는 것으로 밝혀졌다. 

비디오 전체에 걸쳐 다루어진 다른 주제에 대한 시각적 단서를 제공하지만 그렇지 않으면 감지할 수 없었을 수도 있다.

도구와 설문지와의 사용자 상호작용 로그에서 나온 두 가지 관련 결과는 참가자들이 CFB로 더 많은 자료를 탐색할 수 있었고 도구가 정보 검색 작업에 도움이 된다는 것을 알았다(예: 관련성 판단을 내리기 전에 비디오를 적게 보았다).

사용자 연구 참가자 수가 적기 때문에(26명) 상호작용 로그 분석의 모든 결과가 중요한 것은 아니다. 

그러나 우리는 또한 이 새로운 도구에 대한 결론을 도출하기 위해 CFB가 있는 방법과 없는 방법을 분석했다. 
조사 결과는 다음과 같습니다.
참가자들은 CFB를 사용하여 과제를 완료하는 데 평균적으로 더 적은 시간을 소비하는 것으로 보였다. 

시간의 분포 또한 달랐다. CFB와 함께, 그들은 어떤 콘텐츠를 볼 것인지, 또한 어떤 출발점에서 볼 것인지를 결정하는 데 훨씬 더 많은 시간을 보냈다. 

이것은, 그들은 비디오 세트 전반에 걸쳐 그리고 특정 비디오 내에서 더 많은 것을 탐구했습니다. 반면, 참가자들은 CFB로 자료를 보는 시간이 평균적으로 더 적었고, 그들은 더 적은 비디오를 열었다. 

그들은 CFB를 사용할 때 목적적합한 판단에서 실수를 덜 했다(관련된 것으로 표시된 후 참가자가 제거한 부문 수로 입증되었다).

참가자들은 또한 결과 목록에서 더 깊이 탐구했고 CFB가 있는 비디오에서 덜 찾았다. 마지막으로, 참가자들은 관련성 판단에 CFB를 사용하는 데 더 적은 시간을 할애하고 보다 세분화된 콘텐츠 부분을 선택한 것으로 보인다. 

설문지는 대부분의 참가자들이 CFB에 대해 긍정적인 경험을 가지고 있다는 것을 강조했습니다. 

그들은 이 도구가 내용 요약을 제공하고 정보를 찾는 작업에 도움을 주는 데 직관적이고 유용하다는 것을 알았다.
CFB 도구는 콘텐츠 유형에 구애받지 않고 대규모 문서 모음으로 확장할 수 있도록 설계되었으며, 다양한 정보 콘텐츠 양식(예: 비디오, pdf, 오디오 등)에서 자동으로 사용될 수 있다. 

즉, 많은 검색 도구가 수동 주석에 의존하거나 특정 콘텐츠 유형에 특정한 반면, 사용자가 다양한 콘텐츠 양식에 걸쳐 미리 보고 검색할 수 있는 일반적이고 확장 가능한 자동 솔루션은 부족하다. 

상호 작용 도구(Wikification)의 백본은 이러한 기능을 허용합니다. 

우리는 발견된 이점이 교육 비디오를 넘어 광범위한 긴 문서 형식에 사용될 수 있으며 잠재적으로 학습자와 선생님의 손에 있는 강력한 도구가 될 수 있다고 가정한다.
향후 작업에서는 상호 작용 로그 및 사용자 경험에 대한 보다 광범위한 분석을 수행할 계획이다. 

예를 들어, 주제 전문성을 데이터 분석에서 공변량으로 간주하여 사용자 정보 탐색 및 탐색 행동에 영향을 미치는지 여부를 확인할 것이다. 

우리는 또한 쌍별 비교 실험을 통해 시스템 간에 선택된 세그먼트의 품질을 분석하고 비교할 것이다. 

이것은 관련성 판단에 대한 도구의 유용성을 추가로 조사하는 데 도움이 될 것이다. 

우리는 더 다양한 사용자 그룹, 더 많은 정보 검색 및 탐색 작업, 추가 콘텐츠 양식(비디오를 제외하고) 및 기타 고급 제어 조건(예: 비디오 스크립트에서 사용자가 검색할 수 있는 비디오 플레이어)으로 구성된 더 큰 사용자 연구를 실행해야 한다고 제안한다. 검색 및 탐색을 위한 콘텐츠 탐색 도구의 잠재성을 더욱 높일 수 있습니다.
후속 버전의 CFB에서는 엔티티 링크 및 그에 따라 CFB에 고정 크기 조각이 있는 한계를 해결할 계획이다. 

이것은 주제가 변경되고 가변 크기 조각이 있는 곳을 동적으로 추론하는 것을 목표로 한다. 

또한, 사용자의 배경 지식과 목표를 기반으로 궁극적으로 키워드를 개인화해야 하며, 초보 사용자에게 더 일반적인 주제를 보여주고 고급 학습자에게 더 구체적인 개념을 보여주고 사용자의 시기적절한 목표에 맞는 콘텐츠의 일부를 강조해야 한다고 가정한다. 

우리는 또한 사용자가 자료의 '콘텐츠 흐름'을 더 잘 이해하는 데 도움이 되는 시각화뿐만 아니라 자료에서 다루는 주제에 대한 계층 구조를 제공할 수 있는 도구의 다른 설계를 탐구하는 것을 목표로 한다. 

제시된 CFB 도구와 표시된 두 가지 시각화의 주요 한계는 우리가 발견한 것처럼 여전히 오류가 발생하기 쉬운 전사, 번역 및 위키화 알고리듬에 의존한다는 것이다. 

그러나 이러한 것들이 개선됨에 따라 CFB와 같은 탐색 및 시각화 도구도 개선될 것이며, 그렇게 함으로써 정보 검색 작업에 매우 유용한 것으로 입증될 가능성이 높다. 

특히, 우리의 연구가 보여주었듯이, 그들은 사용자가 찾고 있는 것을 찾기 위해 많은 검색 결과를 검토하는 데 오랜 시간을 소비하지 않고도 관련 온라인 자료를 빠르게 찾을 수 있도록 도울 수 있다. 

요약하자면, 학습자와 교육자는 교육 자료를 검색하고 탐구할 때 "더 적게 보고 더 많이 발견할 수 있다".

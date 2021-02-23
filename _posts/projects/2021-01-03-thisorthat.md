---
layout: project
permalink: /:title/
category: main

meta:
  keywords: "HRI, Social Robot"

project:
  title: "This or That"
  subtitle: "The Effect of Robot’s Deictic Expression on User’s Perception"
  type: "Human-Robot Interaction (HRI)"
  logo: "/assets/images/projects/this_or_that/logo.png"
  duration: "2019.12 ~ 2020.02 (3개월)"
  ptype: "Human-Robot Interaction 연구 프로젝트"
  typedetail: "KIST AIㆍ로봇연구소 지능로봇연구단"
  role: "프로젝트 기획, 제품 디자인, 인터랙션 디자인, 프로토타입 개발, 사용자 조사, 데이터 분석"
  supporter1: "Dr. Dahyun Kang (KIST): 프로젝트 기획, 문헌 조사, 인터랙션 디자인, 사용자 조사, 데이터 분석"
  supporter2: "Dr. Eun Ho Kim (KITECH): 프로젝트 기획, 인터랙션 디자인"
  supporter3: "Dr. Sonya S. Kwak (KIST): 프로젝트 지도"
  tools: "SolidWorks, Turtle Bot, Raspberry Pi"
  output: "IEEE/RSJ IROS 2020 학회 논문"

images:
  - image:
    url: "/assets/images/projects/this_or_that/main.jpg"
    alt:

---
---
<br>
<p align="center">
  <img src="/assets/images/projects/this_or_that/intro.png">
  <br>
  <font size="2em" color="gray">포인팅은 언어적, 비언어적 형태로 다양하게 표현될 수 있다.</font>
</p>
<br><br>

<font size="6em">Background</font>
<br>

Design Question: "<span style="background-color:#EBEBEB">소셜 로봇</span>은 <span style="background-color:#EBEBEB">포인팅</span>을 통해 어떻게 사람들과 효과적으로 의사소통할 수 있을까?"
<br><br>

우리는 같은 공간에 있는 사람과 대화할 때 주변의 사물, 장소 등이 자주 주제가 되고, <span style="background-color:#EBEBEB">제스처</span>나 <span style="background-color:#EBEBEB">지시어</span>를 사용해 위치 정보를 공유한다.
로봇은 컴퓨터나 인공지능 스피커와 달리 <span style="background-color:#EBEBEB">언어적 의사소통</span>뿐만 아니라 <span style="background-color:#EBEBEB">비언어적 의사소통</span>을 가능하게 하는 물리적 형태를 가지고 있다.  
<br>
하지만, HRI 측면에서 로봇의 포인팅 연구는 아래와 같이 <span style="background-color:#EBEBEB">제한</span>이 있었다.  
<br><br>

<font size="5em">1) Locative Deixis</font>
<br>

직시어<sup id="F01">[<span style="color:MediumSeaGreen">1</span>](#footnote_1)</sup>는 대화에서 자주 사용된다. 특히, <span style="background-color:#EBEBEB">위치격 직시어(예시: 이거, 저거)</span>는 주변에 있는 특정 대상을 청자 또는 독자가 이해할 수 있도록 언어를 사용해서 참조할 때 사용된다. 하지만, 소셜 로봇은 언어적 의사소통에 있어 대부분 <span style="background-color:#EBEBEB">서술적 직시어(예시: 왼쪽에서 두 번째)</span>를 사용한다. 소셜 로봇의 <span style="background-color:#EBEBEB">인간 친화적 상호작용</span>을 위해 위치격 직시어가 필요하다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/bg1.png">
  <br>
  <font size="2em" color="gray">사람은 다양한 시체 부위를 사용하여 포인팅 제스처를 취할 수 있다.</font>
</p>
<br><br>

<font size="5em">2) Pointing Gesture</font>
<br>

포인팅 제스처는 유아가 첫 단어를 말하기 전 배우는 의사소통 기술 중 하나다<sup id="R01">[<span style="color:gray">1</span>](#reference_1)</sup>. 사람들은 <span style="background-color:#EBEBEB">복잡한 서술을 생략</span>하기 위해 팔, 머리, 눈, 입술, 코와 같은 <span style="background-color:#EBEBEB">다양한 신체 부위</span>를 사용하여 포인팅 제스처를 취한다<sup id="R02">[<span style="color:gray">2</span>](#reference_2)</sup>. 하지만, 대부분의 로봇 포인팅 제스처에 대한 연구는 <span style="background-color:#EBEBEB">손가락</span>으로 가리키는 것으로 제한되었다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/bg2.png">
  <br>
  <font size="2em" color="gray">사람은 다양한 시체 부위를 사용하여 포인팅 제스처를 취할 수 있다.</font>
</p>
<br><br>

<font size="5em">3) Head Pointing</font>
<br>

사람은 <span style="background-color:#EBEBEB">머리</span>를 움직여서 특정 대상을 가리키기도 한다. HRI 연구에 따르면 로봇이 머리를 움직여서 가리키는 것은 인간의 행동과 <span style="background-color:#EBEBEB">비슷한 효과</span>를 나타낸다<sup id="R03">[<span style="color:gray">3</span>](#reference_3)</sup>. 사람은 <span style="background-color:#EBEBEB">시선</span>과 <span style="background-color:#EBEBEB">돌출된 코</span>를 통해 포인팅 제스처를 취할 수 있는 반면에, 소셜 로봇의 머리는 대부분 평면 디스플레이를 사용하기 때문에 정확한 포인팅이 가능한지 알 수 없다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/bg3.png">
  <br>
  <font size="2em" color="gray">사람은 시선과 돌출된 코를 통해 포인팅 제스처를 쉽게 취할 수 있다.</font>
</p>
<br><br><br><br><br><br>

<font size="6em">Goal</font>
<br>

<font size="5em">1) Research Question</font>
<br>

"소셜 로봇의 <span style="background-color:#EBEBEB">언어적, 비언어적 포인팅 표현</span>은 어떻게 디자인될 수 있으며, 가장 효과적인 <span style="background-color:#EBEBEB">인터랙션</span>은 무엇인가?"  
<br><br>

<font size="5em">2) Research Design</font>
<br>

소셜 로봇의 포인팅 관련 <span style="background-color:#EBEBEB">발화</span> 및 <span style="background-color:#EBEBEB">제스처</span>를 다양한 조건으로 프로토타이핑한 후, <span style="background-color:#EBEBEB">상황</span>에 따라 로봇의 표현에 대한 사용자의 인식을 조사한다.  
<br><br><br><br><br><br>

<font size="6em">Study Design</font>
<br>

로봇은 사용자에게 <span style="background-color:#EBEBEB">언어</span>뿐만 아니라 <span style="background-color:#EBEBEB">포인팅 제스처</span>를 통해 물체의 위치를 알릴 수 있다. 또한, 포인팅 제스처는 <span style="background-color:#EBEBEB">시선(eye pointing)</span> 확장이다<sup id="R04">[<span style="color:gray">4</span>](#reference_4)</sup>. 즉, 시선은 포인팅 제스처의 기본이다.  
<br><br>

<font size="5em">1) Independent Variables</font>
<br>

실험 조건은 다음과 같이 총 8가지로 설정하였다.

01. <span style="background-color:#EBEBEB">언어 유형</span>:
  - a. 지시적(deictic)
  - b. 서술적(descriptive)  
<br>

02. <span style="background-color:#EBEBEB">코 포인팅</span>:
  - a. 코가 있는(with nose)
  - b. 코가 없는(without nose)  
<br>

03. <span style="background-color:#EBEBEB">시선</span>:
  - a. 눈이 있는(with eyes)
  - b. 눈이 없는(without eyes)  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/sd1.png">
  <br>
  <font size="2em" color="gray">독립 변수: 언어 유형(2가지) X 코 포인팅(2가지) X 시선(2가지)</font>
</p>
<br><br>

<font size="5em">2) Dependent Variables</font>
<br>
각 실험 조건에 대해서 공통적으로 아래 4가지를 측정하였다.
측정을 통해, 사용자가 각 로봇의 표현 방식에 따라 사용자에게 위치 정보를 얼마나 <span style="background-color:#EBEBEB">효과적</span>으로, <span style="background-color:#EBEBEB">사회적</span>으로, <span style="background-color:#EBEBEB">자연스럽게</span> 제공하는지 확인하였다. 또한, 로봇에 대한 <span style="background-color:#EBEBEB">전반적인 인상</span>을 알아보기위해 제품 평가를 조사하였다.

01. <span style="background-color:#EBEBEB">효율성</span>(perceived effectiveness)<sup id="R05">[<span style="color:gray">5</span>](#reference_5)</sup>
02. <span style="background-color:#EBEBEB">사교성</span>(perceived sociability)<sup id="R06">[<span style="color:gray">6</span>](#reference_6)</sup>
03. <span style="background-color:#EBEBEB">자연스러움</span>(perceived naturalness)<sup id="R05">[<span style="color:gray">5</span>](#reference_5)</sup>
04. <span style="background-color:#EBEBEB">제품 평가</span>(product evaluation)<sup id="R07">[<span style="color:gray">7,</span>](#reference_7)</sup><sup id="R08">[<span style="color:gray"> 8</span>](#reference_8)</sup>  
<br>

전시 안내 상황에서는 아래 2가지를 추가적으로 측정하였다.
01. <span style="background-color:#EBEBEB">역량</span>(perceived competency)<sup id="R06">[<span style="color:gray">6</span>](#reference_6)</sup>
02. <span style="background-color:#EBEBEB">신뢰성</span>(perceived trustworthiness)<sup id="R06">[<span style="color:gray">6</span>](#reference_6)</sup>  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/dv.png">
</p>
<br>
<p align="center">
  <img src="/assets/images/projects/this_or_that/dv2.png">
  <br>
  <font size="2em" color="gray">4가지 공통 측정과 2가지 추가 측정에 대한 아이템</font>
</p>
<br><br>

<font size="5em">3) Prototype Development</font>
<br>

<span style="background-color:#EBEBEB">Wizard of Oz 기법</span><sup id="F02">[<span style="color:MediumSeaGreen">2</span>](#footnote_2)</sup> 실험을 위한 로봇을 디자인하고 개발하였다.  

01. 로봇 프로토타입은 ROS 기반 모바일 로봇인 TurtleBot3<sup id="F03">[<span style="color:MediumSeaGreen">3</span>](#footnote_3)</sup>를 기반으로 방향을 변경하면서 이동할 수 있다.
02. 블루투스 통신으로 로봇의 언어 타입을 제어할 수 있다.
03. Raspberry Pi와 연결된 모니터를 통해 로봇의 시선을 제어할 수 있다.
04. 로봇의 움직임은 블루투스 통신을 통해 조이스틱 컨트롤러를 통해 수동으로 제어된다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/sd2.png">
  <br>
  <font size="2em" color="gray">사용한 소프트웨어: Solidworks, Raspberry Pi, Processing</font>
</p>
<br><br>

<font size="5em">4) Recruitment</font>
<br>

<span style="background-color:#EBEBEB">연구실 조사(in-lab study)</span>로 진행되었으며, <span style="background-color:#EBEBEB">분산분석(ANOVA)</span>을 위해 <span style="background-color:#EBEBEB">혼합 설계(mixed design)</span>하였다.
01. <span style="background-color:#EBEBEB">언어 유형</span>: within design - 피실험자는 <span style="background-color:#EBEBEB">두 가지</span> 언어 유형을 모두 경험한다. (무작위 순서)
02. <span style="background-color:#EBEBEB">코 포인팅</span>: within design - 피실험자는 <span style="background-color:#EBEBEB">두 가지</span> 코 포인팅을 모두 경험한다. (무작위 순서)
03. <span style="background-color:#EBEBEB">시선</span>: between design - 피실험자는 <span style="background-color:#EBEBEB">한 가지</span> 시선을 경험한다.  

피실험자: 48명 (23세~37세, 여성 26명, 남성 22명)

<br><br><br><br><br><br>

<font size="6em">Experiments</font>
<br>

로봇이 사용자와 상호작용하는 상황에 따라, <span style="background-color:#EBEBEB">2가지</span>의 실험을 진행하였다.

01. <span style="background-color:#EBEBEB">자리 안내</span>(seat guide): 로봇이 사용자에게 <span style="background-color:#EBEBEB">명령문</span>을 사용하는 상황
02. <span style="background-color:#EBEBEB">전시 안내</span>(exhibition guide): 로봇이 사용자에게 <span style="background-color:#EBEBEB">평서문</span>을 사용하는 상황
<br><br>

<font size="5em">1) Seat Guide</font>
<br>

로봇은 피실험자를 맞이하고 앉을 자리로 안내한다. 피실험자는 연구실에 배치된 5개의 의자 중 로봇이 <span style="background-color:#EBEBEB">포인팅 하는 의자에 앉도록 요청</span>받았다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/sg1.png">
  <br>
  <font size="2em" color="gray">로봇이 포인팅 하는 의자에 앉은 피실험자</font>
</p>
<br>

피실험자는 무작위 순서로 총 <span style="background-color:#EBEBEB">4번의 착석</span> 요청을 받았으며, 각 착석 이후에 로봇의 <span style="background-color:#EBEBEB">인상을 평가</span>했다. 로봇의 언어 및 제스처 표현 예는 다음과 같다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/sg2.png">
</p>  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/sg3.png">
</p>  
<br><br><br>

<font size="5em">2) Exhibition Guide</font>
<br>

피실험자는 안내 로봇을 통해 <span style="background-color:#EBEBEB">로봇 쇼룸에 전시된 로봇에 대한 설명</span>을 듣는다. 안내 로봇은 전시된 5개의 로봇을 하나씩 포인팅 하면서 설명하고, 피실험자는 메모지에 안내 로봇이 <span style="background-color:#EBEBEB">포인팅 한 순서대로 메모</span>한다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/eg1.png">
  <br>
  <font size="2em" color="gray">안내 로봇이 포인팅 하는 로봇에 대한 설명을 메모하고 있는 피실험자</font>
</p>
<br>

피실험자는 무작위 순서로 총 <span style="background-color:#EBEBEB">4번의 조건을</span> 경험했으며, 각 조건 이후에 로봇의 <span style="background-color:#EBEBEB">인상을 평가</span>했다. 로봇의 언어 및 제스처 표현 예는 다음과 같다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/eg2.png">
</p>  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/eg3.png">
</p>  
<br><br><br><br><br><br>

<font size="6em">Results</font>
<br>

실험을 통해 각 조건의 로봇이 사용자의 인식에 미치는 영향을 조사하기 위해 <span style="background-color:#EBEBEB">이원 반복측정 분산분석(two-way repeatedly measured ANOVA)</span>을 수행했다.  
<br><br>

<font size="5em">1) Seat Guide</font>
<br>

로봇의 효율성, 사교성, 자연스러움 및 제품 평가 측정은 크론바 알파 값 0.6 이상으로, 모든 문항에 대해 <span style="background-color:#EBEBEB">유의</span>한 결과가 나왔다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/results1.png">
  <br>
  <font size="2em" color="gray">각 측정에 대한 신뢰도 분석 후 크론바 알파 값</font>
</p>
<br>

각 측정의 유의한 <span style="background-color:#EBEBEB">주 효과(main effect)</span>는 다음과 같다.
01. <span style="background-color:#EBEBEB">코 포인팅</span>이 <span style="background-color:#EBEBEB">효율성</span>에 미치는 주 효과는 유의미했다. <font size="2em">(<i>F</i><sub>(1,46)</sub> = 21.171, <i>p</i> < 0.0005)</font>  
02. <span style="background-color:#EBEBEB">코 포인팅</span>이 <span style="background-color:#EBEBEB">사교성</span>에 미치는 주 효과는 유의미했다. <font size="2em">(<i>F</i><sub>(1,46)</sub> = 3.870, <i>p</i> = 0.055)</font>  
03. <span style="background-color:#EBEBEB">언어 유형</span>이 <span style="background-color:#EBEBEB">제품 평가</span>에 미치는 주 효과는 유의미했다. <font size="2em">(marginally significant, <i>F</i><sub>(1,46)</sub> = 2.955, <i>p</i> = 0.092)</font>   
04. <span style="background-color:#EBEBEB">코 포인팅</span>이 <span style="background-color:#EBEBEB">제품 평가</span>에 미치는 주 효과는 유의미했다. <font size="2em">(<i>F</i><sub>(1,46)</sub> = 7.736, <i>p</i> = 0.008)</font>  
<br>

<span style="background-color:#EBEBEB">주 효과</span>에서 피실험자의 인식은 다음과 같다.
01. <span style="background-color:#EBEBEB">자리 안내</span> 상황에서, <span style="background-color:#EBEBEB">코가 있는</span> 로봇이 코가 없는 로봇보다 더 <span style="background-color:#EBEBEB">효율적</span>이라고 인식했다. <font size="2em"><i>M</i><sub>withnose</sub> = 5.32, <i>SD</i> = 0.15 vs. <i>M</i><sub>withoutnose</sub> = 4.54, <i>SD</i> = 0.19)</font>  
02. <span style="background-color:#EBEBEB">자리 안내</span> 상황에서, <span style="background-color:#EBEBEB">코가 있는</span> 로봇이 코가 없는 로봇보다 더 <span style="background-color:#EBEBEB">사교적</span>이라고 인식했다. <font size="2em"><i>M</i><sub>withnose</sub> = 4.68, <i>SD</i> = 0.16 vs. <i>M</i><sub>withoutnose</sub> = 4.41, <i>SD</i> = 0.17)</font>  
03. <span style="background-color:#EBEBEB">자리 안내</span> 상황에서, <span style="background-color:#EBEBEB">서술적</span>인 발화를 하는 로봇이 지시적인 발화를 하는 로봇보다 더 <span style="background-color:#EBEBEB">긍정적</span>이라고 인식했다. <font size="2em"><i>M</i><sub>deictic</sub> = 4.70, <i>SD</i> = 0.17 vs. <i>M</i><sub>descriptive</sub> = 5.00, <i>SD</i> = 0.15)</font>  
04. <span style="background-color:#EBEBEB">자리 안내</span> 상황에서, <span style="background-color:#EBEBEB">코가 있는</span> 로봇이 코가 없는 로봇보다 더 <span style="background-color:#EBEBEB">긍정적</span>이라고 인식했다. <font size="2em"><i>M</i><sub>withnose</sub> = 5.01, <i>SD</i> = 0.15 vs. <i>M</i><sub>withoutnose</sub> = 4.70, <i>SD</i> = 0.15)</font>  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/results3.png">
</p>
<br>
<p align="center">
  <img src="/assets/images/projects/this_or_that/results4.png">
</p>
<br><br>

로봇이 포인팅 한 자리에 피실험자가 앉은 확률을 아래 표와 같이 정리하였다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/results5.png">
</p>  
<br><br>

<font size="5em">2) Exhibition Guide</font>
<br>

로봇의 효율성, 사교성, 자연스러움, 제품 평가, 역량 및 신뢰성 측정은 크론바 알파 값 0.6 이상으로, 모든 문항에 대해 <span style="background-color:#EBEBEB">유의</span>한 결과가 나왔다.  
<br>

<p align="center">
  <img src="/assets/images/projects/this_or_that/results2.png">
  <br>
  <font size="2em" color="gray">각 측정에 대한 신뢰도 분석 후 크론바 알파 값</font>
</p>
<br>

각 측정의 유의한 <span style="background-color:#EBEBEB">주 효과(main effect)</span>는 다음과 같다.
01. <span style="background-color:#EBEBEB">언어 유형</span>이 <span style="background-color:#EBEBEB">효율성</span>에 미치는 주 효과는 유의미했다. <font size="2em">(<i>F</i><sub>(1,46)</sub> = 94.242, <i>p</i> < 0.0005)</font>   
02. <span style="background-color:#EBEBEB">코 포인팅</span>이 <span style="background-color:#EBEBEB">효율성</span>에 미치는 주 효과는 유의미했다. <font size="2em">(<i>F</i><sub>(1,46)</sub> = 53.908, <i>p</i> < 0.0005)</font>   
<br>

<span style="background-color:#EBEBEB">주 효과</span>에서 피실험자의 인식은 다음과 같다.
01. <span style="background-color:#EBEBEB">전시 안내</span> 상황에서, <span style="background-color:#EBEBEB">서술적</span>인 발화를 하는 로봇이 지시적인 발화를 하는 로봇보다 더 <span style="background-color:#EBEBEB">효율적</span>이라고 인식했다. <font size="2em"><i>M</i><sub>deictic</sub> = 4.29, <i>SD</i> = 0.17 vs. <i>M</i><sub>descriptive</sub> = 5.63, <i>SD</i> = 0.12)</font>  
02. <span style="background-color:#EBEBEB">전시 안내</span> 상황에서, <span style="background-color:#EBEBEB">코가 있는</span> 로봇이 코가 없는 로봇보다 더 <span style="background-color:#EBEBEB">효율적</span>이라고 인식했다. <font size="2em"><i>M</i><sub>withnose</sub> = 5.43, <i>SD</i> = 0.15 vs. <i>M</i><sub>withoutnose</sub> = 4.48, <i>SD</i> = 0.14)</font>  
<br>

<br><br><br><br><br><br>


<font size="6em">Publication</font>
<br>

[<u>This or That: The Effect of Robot’s Deictic Expression on User’s Perception</u> <br> <font size="2em"><u>2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</u></font>](https://ieeexplore.ieee.org/document/9341067)
<br><br><br><br><br><br>


---

**References**  
<a name="reference_1"><font size="2em" color="gray">1.</font></a> [<font size="2em"><u>Pointing: Where Language, Culture, and Cognition Meet</u></font>](https://books.google.co.kr/books?hl=ko&lr=&id=JlN4AgAAQBAJ&oi=fnd&pg=PP1&dq=Pointing:+Where+Language,+Culture,+and+Cognition+Meet&ots=pP_hGHknJb&sig=fk5eCywXFbZW79pPA4QPUP5An-Q#v=onepage&q=Pointing%3A%20Where%20Language%2C%20Culture%2C%20and%20Cognition%20Meet&f=false)<font size="2em"> (2003) by Sotaro Kita</font> [↩](#R01)  
<a name="reference_2"><font size="2em" color="gray">2.</font></a> [<font size="2em"><u>The Role of Gesture in Communication and Thinking</u></font>](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=51D1CBC4966CC0EDAAF34593B83E30F3?doi=10.1.1.462.5492&rep=rep1&type=pdf)<font size="2em"> (1999) by Susan Goldin-Meadow in Trends in Cognitive Sciences</font> [↩](#R02)  
<a name="reference_3"><font size="2em" color="gray">3.</font></a> [<font size="2em"><u>We Are Not Contortionists: Coupled Adaptive Learning for Head and Body Orientation Estimation in Surveillance Video</u></font>](https://ieeexplore.ieee.org/document/6247845)<font size="2em"> (2012) by Cheng Chen and Jean-Marc Odobez in IEEE Conference on Computer Vision and Pattern Recognition</font> [↩](#R03)  
<a name="reference_4"><font size="2em" color="gray">4.</font></a> [<font size="2em"><u>Becoming Human: From Pointing Gestures to Syntax</u></font>](https://books.google.co.kr/books?hl=ko&lr=&id=jK5nk7iDgSYC&oi=fnd&pg=PT1&dq=Becoming+Human:+From+Pointing+Gestures+to+Syntax&ots=DpGBCF5PdV&sig=_Q7GH-Ar1iBDJupb8caNUO2sg98#v=onepage&q=Becoming%20Human%3A%20From%20Pointing%20Gestures%20to%20Syntax&f=false)<font size="2em"> (2011) by Teresa Bejarano</font> [↩](#R04)  
<a name="reference_5"><font size="2em" color="gray">5.</font></a> [<font size="2em"><u>Robot Deictics: How Gesture and Context Shape Referential Communication</u></font>](https://ieeexplore.ieee.org/abstract/document/8542607)<font size="2em"> (2014) by Allison Sauppé and Bilge Mutlu in ACM/IEEE HRI</font> [↩](#R05)  
<a name="reference_6"><font size="2em" color="gray">6.</font></a> [<font size="2em"><u>Rhetorical Robots: Making Robots More Effective Speakers Using Linguistic Cues of Expertise</u></font>](https://ieeexplore.ieee.org/abstract/document/6483608)<font size="2em"> (2013) by Sean Andrist, Erin Spannan and Bilge Mutlu in ACM/IEEE HRI</font> [↩](#R06)  
<a name="reference_7"><font size="2em" color="gray">7.</font></a> [<font size="2em"><u>Adoption of New and Really New Products: The Effects of Self-Regulation Systems and Risk Salience</u></font>](https://doi.org/10.1509%2Fjmkr.44.2.251)<font size="2em"> (2007) by Michal Herzenstein, Steven S. Posavac and J. Joško Brakus in Journal of Marketing Research</font> [↩](#R07)  
<a name="reference_8"><font size="2em" color="gray">8.</font></a> [<font size="2em"><u>The Role of Imagination-Focused Visualization on New Product Evaluation</u></font>](https://doi.org/10.1509%2Fjmkr.46.1.46)<font size="2em"> (1989) by Min Zhao, Steve Hoeffler and Darren W. Dahl in Journal of Marketing Research</font> [↩](#R08)  

<br>

**Footnotes**  
<a name="footnote_1"><font size="2em" color="MediumSeaGreen">1.</font></a> [<font size="2em">문맥상 단어가 사용된 맥락, 시간, 공간, 청자와 화자 따위의 발화 상황을 고려해야만 의미 파악이 되는 지시 표현. (예시: '나', '너'와 같은 인칭 대명사나 '이곳', '여기', '저기' 같은 지시어) <u>[출처: 네이버 국어사전]</u></font>](https://ko.dict.naver.com/#/entry/koko/2416902403024234bfed8ca7887a3441) [↩](#F01)  
<a name="footnote_2"><font size="2em" color="MediumSeaGreen">2.</font></a> <font size="2em">Wizard of Oz 기법: 개발되지 않은 서비스를 실제 서비스처럼 착각하게 만들어 테스트를 진행하는 방법</font> [↩](#F02)   
<a name="footnote_3"><font size="2em" color="MediumSeaGreen">3.</font></a> [<font size="2em"><u>ROBOTIS TurtleBot3</u></font>](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/) [↩](#F03)   

<br><br><br>

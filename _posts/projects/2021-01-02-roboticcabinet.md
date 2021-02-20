---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "HRI, Robotic Furniture"

project:
  title: "Robotic Cabinets"
  subtitle: "Designing Robotic Cabinets That Assist Users’ Tidying Behaviors"
  type: "Human-Robot Interaction (HRI)"
  logo: "/assets/images/projects/robotic_cabinet/logo.png"
  duration: "2019.06 ~ 08 (3개월)"
  ptype: "Human-Robot Interaction 연구 프로젝트"
  typedetail: "기여도: 60% | KIST AIㆍ로봇연구소 지능로봇연구단"
  role: "프로젝트 기획, 문헌 조사, 인터랙션 디자인, 프로토타입 개발, 사용자 조사, 데이터 분석"
  supporter1: "Dr. Dahyun Kang (KIST): 프로젝트 기획, 데이터 분석"
  supporter2: "Dr. Sonya S. Kwak (KIST): 프로젝트 지도"
  tools: "Arduino, SolidWorks"
  output: "제품 프로토타입, IEEE RO-MAN 2020 학회 논문"


images:
  - image:
    url: "/assets/images/projects/robotic_cabinet/main.jpg"
    alt:

---
---
<br>
<!-- ![background](/assets/images/projects/modular_smart_speaker/bg.png) -->
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/intro.png">
  <br>
  <font size="2em" color="gray">유기체 지향 로봇인 SoftBank사의 Pepper와 객체 지향 로봇인 iRobot사의 Roomba.</font>
</p>
<br><br>

<font size="6em">Background</font>
<br>

Design Question: "사람들의 <span style="background-color:#EBEBEB">정리 정돈</span>을 <span style="background-color:#EBEBEB">로봇 기술</span>을 통해 도와줄 수 있는 방법은 무엇일까?"  
<br>

<font size="5em">1) Problem</font>
<br>
컴퓨터가 개발되면서 사람들은 사운드, 비디오, 이미지 등 다양한 파일을 만들거나 다운로드하기 시작했다.
수납 가구에 물건을 정렬하고 저장하는 방법과 유사하게, 디지털 파일을 지정된 폴더에 정렬하고 저장할 수 있다.
그러나 디지털 파일의 위치를 쉽게 <span style="background-color:#EBEBEB">검색</span>할 수 있는 컴퓨터와 달리 수납 가구는 물건이 있는 위치를 <span style="background-color:#EBEBEB">기억</span>해야 한다.

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/bg.png">
  <br>
  <font size="2em" color="gray">수납 가구는 물건이 있는 위치를 검색할 수 없다.</font>
</p>
<br><br>

<font size="5em">2) Robot Design Approach</font>
<br>

로봇 디자인 방식에 따르면, 로봇의 <span style="background-color:#EBEBEB">종류</span>는 아래와 같이 나뉠 수 있다<sup id="R01">[<span style="color:gray">1</span>](#reference_1)</sup>.
01. <span style="background-color:#EBEBEB">유기체</span> 지향 로봇(organism-oriented robot): 사람, 동물과 같이 살아있는 유기체와 유사한 형태와 기능이 있는 로봇
02. <span style="background-color:#EBEBEB">객체</span> 지향 로봇(object-oriented robot): 로봇 청소기와 같이 일반 제품에 로봇 기술을  적용한 로봇

또한, <span style="background-color:#EBEBEB">객체 지향 로봇</span>은 유기체 지향 로봇보다 소비자에게 더 자주 <span style="background-color:#EBEBEB">수용</span>될 가능성이 있다<sup id="R01">[<span style="color:gray">1</span>](#reference_1)</sup>.
객체 지향 로봇은 기존 제품의 <span style="background-color:#EBEBEB">로봇화</span>에 중점을 두며, 우산과 액자 같은 작은 생활용품부터 서랍, 의자, 오토만 등 가구에 이르기까지 다양한 유형의 로봇 제품으로 개발될 수 있다.  

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/bg2.png">
  <br>
  <font size="2em" color="gray">객체 지향 로봇은 유기체 지향 로봇보다 소비자에게 더 자주 수용될 가능성이 있다.</font>
</p>
<br><br>

<font size="5em">3) Robotic Furniture</font>
<br>

최근 <span style="background-color:#EBEBEB">로보틱 가구</span>는 새로운 스마트 라이프 스타일의 패러다임을 도입하여 대중의 관심을 끌고 있다.
IKEA와 Ori는 작은 공간에 사는 사람들을 위해 설계된 ROGNAN<sup id="F01">[<span style="color:MediumSeaGreen">1</span>](#footnote_1)</sup>이라는 새로운 로보틱 가구 시스템을 개발했다.  
<br>

<br>
<p align="center">
  <a href="https://youtu.be/5lqwN60rzqY">
  <img src="/assets/images/projects/robotic_cabinet/youtube.png">
  </a>
  <br>
  <font size="2em" color="gray">ROGNAN은 옷장, 소파, 책상, 침대 등 다양한 가구로 구성되어 있으며 각 가구는 사용자가 공간을 효율적으로 사용할 수 있도록 위치를 변경할 수 있다.</font>
</p>
<br>

특히, 효율적인 <span style="background-color:#EBEBEB">공간 정리</span>를 원하는 오늘날 사람들의 요구에 알맞게 다양한 <span style="background-color:#EBEBEB">로보틱 수납 가구</span>의 개발이 필요하다.
가구는 인간의 행동이나 자세를 직접적으로 연관이 되는 제품이므로 사용성, 인체공학 등 다양한 디자인 문제를 신중히 고려해야 한다.
<br><br><br><br><br><br>

<font size="6em">Goal</font>
<br>

<font size="5em">1) Research Question</font>
<br>

"수납 가구의 <span style="background-color:#EBEBEB">로봇화</span>는 어떻게 될 수 있으며 사용자들이 선호하는 <span style="background-color:#EBEBEB">인터랙션</span>은 무엇인가?"
<br><br><br>

<font size="5em">2) Research Design</font>
<br>

사용자의 수납 가구 <span style="background-color:#EBEBEB">사용 패턴</span>을 관찰하여 로보틱 수납 가구에 대한 <span style="background-color:#EBEBEB">디자인 인사이트</span>를 도출하고, 사용자의 요구를 고려하여 <span style="background-color:#EBEBEB">프로토타이핑</span>한다.
로보틱 수납 가구와의 효과적인 상호 작용 방법을 찾기 위해 개발된 프로토타입에 대한 사용자의 <span style="background-color:#EBEBEB">인식</span>을 평가한다.

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/goal.png">
</p>
<br><br><br><br><br>

<font size="6em">Study Design</font>
<br>

<font size="5em">1) Design Requirements</font>
<br>

수납장, 서랍장 등 수납 가구 사용 시 사용자의 <span style="background-color:#EBEBEB">문제점</span>과 <span style="background-color:#EBEBEB">요구</span>를 파악하기 위해 인터뷰를 실시했다.  

질문은 다음과 같다.
01. 수납 가구를 사용할 때 어떤 어려움이 있었는지 알려주세요.
02. 위의 문제를 기술로 해결할 수 있는 방법에 대해 의견을 공유해 주세요.

질문에 대한 답변은 아래 표와 같이 정리할 수 있다.

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/sd.png">
</p>
<br>

수납 가구에 대한 사용자의 주된 문제점은 물건 <span style="background-color:#EBEBEB">정리</span>와 물건 <span style="background-color:#EBEBEB">찾기</span>였다.  
<br><br>

<font size="5em">2) Prototype Development</font>
<br>
인터뷰 결과를 바탕으로, 사용자의 정리 정돈 활동을 지원하는 로보틱 수납 가구를 만들기 위해 <span style="background-color:#EBEBEB">캐비닛</span>을 선택했다.  
로보틱 수납 가구의 디자인 요구에서 선택된 인터랙션은 다음과 같다.

01. 물건 <span style="background-color:#EBEBEB">정리</span>: 사용자의 분류 기준에 따라 자동으로 <span style="background-color:#EBEBEB">물건 분류</span>(A)
02. 물건 <span style="background-color:#EBEBEB">찾기</span>: 물건을 찾기 위한 <span style="background-color:#EBEBEB">음성 인식</span>(C), 물건이 들어있는 수납 가구의 <span style="background-color:#EBEBEB">문이나 서랍이 열림</span>(F)
<br><br>

설계된 인터랙션 시나리오는 다음과 같다.
01. 사용자가 "캐비닛"을 호출하고 음성 명령으로 <span style="background-color:#EBEBEB">물건을 넣을 위치</span>를 물으면, 해당 위치의 <span style="background-color:#EBEBEB">문이 열린다</span>.
02. 사용자가 “캐비닛”을 호출하고 음성 명령으로 <span style="background-color:#EBEBEB">물건이 있는 위치</span>를 물으면, 해당 위치의 <span style="background-color:#EBEBEB">문이 열린다</span>.
<br>

<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/sd2.png">
</p>
<br><br>

인터랙션을 적용하여 <span style="background-color:#EBEBEB">Wizard of Oz 기법</span><sup id="F02">[<span style="color:MediumSeaGreen">2</span>](#footnote_2)</sup> 실험을 위한 로보틱 캐비닛을 개발하였다.
<br>
01. 서보 모터를 이용하여 캐비닛의 문을 열 수 있다.
02. 적외선 통신을 통해 실험자는 캐비닛의 서보 모터를 제어할 수 있다.

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/sd3.png">
  <br>
  <font size="2em" color="gray">사용한 소프트웨어: Arduino, SolidWorks</font>
</p>
<br><br>

<font size="5em">3) Independent Variables</font>
<br>

실험 조건은 다음과 같이 총 3가지로 설정하였다.  
01. 로보틱 캐비닛의 <span style="background-color:#EBEBEB">지능화 정도</span>:
  - a. <span style="background-color:#EBEBEB">일반</span> 캐비닛
  - b. 물건 <span style="background-color:#EBEBEB">정리를 돕는</span> 로보틱 캐비닛
  - c. 물건 <span style="background-color:#EBEBEB">찾기를 돕는</span> 로보틱 캐비닛
<br><br><br>

<font size="5em">4) Dependent Variables</font>
<br>

각 실험 조건에 대해서 아래 3가지를 측정하였다.
측정을 통해, 사용자가 각 조건의 로보틱 캐비닛를 얼마나 <span style="background-color:#EBEBEB">유용</span>하게 생각했는지, 얼마나 <span style="background-color:#EBEBEB">사용이 편리</span>하다고 생각했는지, 얼마나 <span style="background-color:#EBEBEB">지능적인 존재</span>로 인지했는지, 얼마나 제품에 대해 <span style="background-color:#EBEBEB">만족</span>하는지 확인하였다.
01. <span style="background-color:#EBEBEB">유용성</span>(perceived usefulness)<sup id="R02">[<span style="color:gray">2</span>](#reference_2)</sup>
02. <span style="background-color:#EBEBEB">사용 편의성</span>(perceived ease of use)<sup id="R02">[<span style="color:gray">2</span>](#reference_2)</sup>
03. <span style="background-color:#EBEBEB">지능</span>(perceived intelligence)<sup id="R03">[<span style="color:gray">3</span>](#reference_3)</sup>
04. <span style="background-color:#EBEBEB">제품 평가</span>(product evaluation)<sup id="R04">[<span style="color:gray">4,</span>](#reference_4)</sup><sup id="R05">[<span style="color:gray"> 5</span>](#reference_5)</sup>

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/sd4.png">
</p>

<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/sd5.png">
  <br>
  <font size="2em" color="gray">4가지 측정에 대한 아이템</font>
</p>
<br><br>

<font size="5em">5) Recruitment</font>
<br>

<span style="background-color:#EBEBEB">연구실 조사(in-lab study)</span>로 진행되었으며, <span style="background-color:#EBEBEB">분산분석(ANOVA)</span>를 위해 <span style="background-color:#EBEBEB">집단내 설계(within design)</span>하였다.
01. <span style="background-color:#EBEBEB">지능화 정도</span>: within design - 피실험자는 로보틱 캐비닛의 <span style="background-color:#EBEBEB">세 가지</span> 조건을 모두 경험한다. (무작위 순서)

피실험자: 16명 (20~30, 여성 7명, 남성 9명)
<br><br><br>

<font size="5em">6) Procedure</font>
<br>

피실험자는 본 실험에 앞서 <span style="background-color:#EBEBEB">20가지 생활용품</span>을 최대 4칸의 로보틱 캐비닛에 <span style="background-color:#EBEBEB">자신의 기준</span>에 맞게 분류한다. 그 기준에 맞춰 로보틱 캐비닛에  물건을 넣고 찾는 본 실험을 진행한다.  
<br>

<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/sd6.png">
  <br>
  <font size="2em" color="gray">20가지 생활용품에 대해서 피실험자마다 다른 분류 기준을 가지고 있다.</font>
</p>
<br><br>

피실험자는 무작위 순서로 로보틱 캐비닛의 3가지 조건을 모두 경험하며, 각 조건마다 <span style="background-color:#EBEBEB">3가지의 물건을 넣고 찾는 행위</span>를 반복한다.

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/sd7.png">
</p>
<br>

로보틱 캐비닛의 조건은 모든 피실험자에게 <span style="background-color:#EBEBEB">무작위 순서</span>로 배정되어있으며 실험 과정은 다음과 같다.  
(물건 정리를 돕는 로보틱 캐비닛의 경우)
01. 피실험자는 20가지 생활용품을 자신의 기준에 맞게 최대 4칸의 캐비닛에 분류한다.  
[실험자는 피실험자의 기준을 표에 기록한다.]
02. 실험자는 임의의 물건을 피실험자의 기준에 맞게 정리하도록 요청한다.
03. 피실험자는 로보틱 캐비닛에게 물건을 어디에 넣어야 하는지 묻는다.  
[실험자는 피실험자의 기준에 맞게 해당하는 칸의 문을 적외선 통신으로 연다.]
04. 피실험자는 로보틱 캐비닛의 열린 칸에 물건을 넣는다.
05. 실험자는 피실험자의 기준에 맞게 물건을 로보틱 캐비닛에 정리하고, 임의의 물건을 찾도록 요청한다.
06. 피실험자는 물건의 위치를 기억하고 찾는다.
07. 피실험자는 한 가지 조건을 경험한 후, 해당 조건의 인상 평가를 진행한다.
08. 나머지 조건에 대해서도 2~7번과 같이 반복한다.

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/sd8.png">
  <br>
  <font size="2em" color="gray">물건을 분류하고 있는 피실험자</font>
</p>
<br><br><br><br><br><br>

<font size="6em">Results</font>
<br>

<br><br><br><br><br><br>

<font size="6em">Publication</font>
<br>

[<u>Designing Robotic Cabinets That Assist Users’ Tidying Behaviors</u> <br> <font size="2em"><u>2020 29th IEEE International Conference on Robot and Human Interactive Communication (RO-MAN)</u></font>](https://ieeexplore.ieee.org/abstract/document/9223550)
<br><br><br><br><br><br>

---
**References**  

<a name="reference_1"><font size="2em" color="gray">1.</font></a> [<font size="2em"><u>The Effects of Organism- Versus Object-Based Robot Design Approaches on the Consumer Acceptance of Domestic Robots</u></font>](https://link.springer.com/article/10.1007/s12369-016-0388-1)<font size="2em"> (2017) by Sonya S. Kwak, Jun San Kim and Jung Ju Choi in International Journal of Social Robotics</font> [↩](#R01)  
<a name="reference_2"><font size="2em" color="gray">2.</font></a> [<font size="2em"><u>Perceived Usefulness, Perceived Ease of Use, and User Acceptance of Information Rechnology</u></font>](https://www.jstor.org/stable/249008?seq=1)<font size="2em"> (1989) by Fred D. Davis in MIS Quarterly</font> [↩](#R02)  
<a name="reference_3"><font size="2em" color="gray">3.</font></a> [<font size="2em"><u>Measurement Instruments for the Anthropomorphism, Animacy, Likeability, Perceived Intelligence, and Perceived Safety of Robots</u></font>](https://link.springer.com/article/10.1007/s12369-008-0001-3)<font size="2em"> (2009) by Christoph Bartneck, Dana Kulić, Elizabeth Croft and Susana Zoghbi in International Journal of Social Robotics</font> [↩](#R03)  
<a name="reference_4"><font size="2em" color="gray">4.</font></a> [<font size="2em"><u>Adoption of New and Really New Products: The Effects of Self-Regulation Systems and Risk Salience</u></font>](https://doi.org/10.1509%2Fjmkr.44.2.251)<font size="2em"> (2007) by Michal Herzenstein, Steven S. Posavac and J. Joško Brakus in Journal of Marketing Research</font> [↩](#R04)  
<a name="reference_5"><font size="2em" color="gray">5.</font></a> [<font size="2em"><u>The Role of Imagination-Focused Visualization on New Product Evaluation</u></font>](https://doi.org/10.1509%2Fjmkr.46.1.46)<font size="2em"> (1989) by Min Zhao, Steve Hoeffler and Darren W. Dahl in Journal of Marketing Research</font> [↩](#R05)  

<br>

**Footnotes**  

<a name="footnote_1"><font size="2em" color="MediumSeaGreen">1.</font></a> [<font size="2em"><u>ROGNAN robotic furniture for small space living</u></font>](https://ikea.today/rognan-robotic-furniture-for-small-space-living/) [↩](#F01)  
<a name="footnote_2"><font size="2em" color="MediumSeaGreen">2.</font></a> <font size="2em">Wizard of Oz 기법: 개발되지 않은 서비스를 실제 서비스처럼 착각하게 만들어 테스트를 진행하는 방법</font> [↩](#F02)   

<br><br><br>

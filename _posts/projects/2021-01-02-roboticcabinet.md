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

Design Question: "사람들의 **정리 정돈**을 **로봇 기술**을 통해 도와줄 수 있는 방법은 무엇일까?"  
<br>

<font size="5em">1) Problem</font>
<br>
컴퓨터가 개발되면서 사람들은 사운드, 비디오, 이미지 등 다양한 파일을 만들거나 다운로드하기 시작했다.
수납 가구에 물건을 정렬하고 저장하는 방법과 유사하게, 디지털 파일을 지정된 폴더에 정렬하고 저장할 수 있다.
그러나 디지털 파일의 **위치를 쉽게 검색**할 수 있는 컴퓨터와 달리 수납 가구는 물건이 있는 위치를 **기억**해야 한다.

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/bg.png">
  <br>
  <font size="2em" color="gray">수납 가구는 물건이 있는 위치를 검색할 수 없다.</font>
</p>
<br><br>

<font size="5em">2) Robot Design Approach</font>
<br>

로봇 **디자인 방식**에 따르면, 로봇의 **종류**는 아래와 같이 나뉠 수 있다<sup id="R01">[<span style="color:gray">1</span>](#reference_1)</sup>.
01. **유기체 지향 로봇**(organism-oriented robot): 사람, 동물과 같이 살아있는 **유기체**와 유사한 형태와 기능이 있는 로봇
02. **객체 지향 로봇**(object-oriented robot): 로봇 청소기와 같이 일반 **제품**에 로봇 기술을  적용한 로봇

또한, **객체** 지향 로봇은 유기체 지향 로봇보다 소비자에게 더 자주 **수용**될 가능성이 있다<sup id="R01">[<span style="color:gray">1</span>](#reference_1)</sup>.
**객체** 지향 로봇은 기존 제품의 **로봇화**에 중점을 두며, 우산과 액자 같은 작은 생활용품부터 서랍, 의자, 오토만 등 가구에 이르기까지 다양한 유형의 로봇 제품으로 개발될 수 있다.  

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/bg2.png">
  <br>
  <font size="2em" color="gray">객체 지향 로봇은 유기체 지향 로봇보다 소비자에게 더 자주 수용될 가능성이 있다.</font>
</p>
<br><br>

<font size="5em">3) Robotic Furniture</font>
<br>

최근 **로보틱 가구**는 새로운 스마트 라이프 스타일의 패러다임을 도입하여 대중의 관심을 끌고 있다.
IKEA와 Ori는 작은 공간에 사는 사람들을 위해 설계된 ROGNAN<sup id="F01">[<span style="color:MediumSeaGreen">1</span>](#footnote_1)</sup>이라는 새로운 로봇 가구 시스템을 개발했다.  
<br>

<iframe width="800" height="450" src="https://www.youtube.com/embed/5lqwN60rzqY" frameborder="0" allowfullscreen></iframe>
<p align="center"><font size="2em" color="gray">ROGNAN은 옷장, 소파, 책상, 침대 등 다양한 가구로 구성되어 있으며 각 가구는 사용자가 공간을 효율적으로 사용할 수 있도록 위치를 변경할 수 있다.</font></p>
<br>

특히, 효율적인 **공간 정리**를 원하는 오늘날 사람들의 요구에 알맞게 다양한 **로봇 수납 가구**의 개발이 필요하다.
가구는 인간의 **행동**이나 **자세**를 직접적으로 연관이 되는 제품이므로 **사용성**, **인체공학** 등 다양한 디자인 문제를 신중히 고려해야 한다.
<br><br><br><br><br><br>

<font size="6em">Goal</font>
<br>

<font size="5em">1) Research Question</font>
<br>

"수납 가구의 **로봇화**는 어떻게 될 수 있으며 사용자들이 선호하는 **인터랙션**은 무엇인가?"
<br><br><br>

<font size="5em">2) Research Design</font>
<br>

사용자의 수납 가구 **사용 패턴**을 관찰하여 로보틱 수납 가구에 대한 **디자인 인사이트**를 도출하고, 사용자의 요구를 고려하여 **프로토타이핑**한다.
로보틱 수납 가구와의 효과적인 상호 작용 방법을 찾기 위해 개발된 프로토타입에 대한 사용자의 **인식**을 평가한다.

<br>
<p align="center">
  <img src="/assets/images/projects/robotic_cabinet/goal.png">
</p>
<br><br><br><br><br>

<font size="6em">Publication</font>
<br>

[<u>Designing Robotic Cabinets That Assist Users’ Tidying Behaviors</u> <br> <font size="2em"><u>2020 29th IEEE International Conference on Robot and Human Interactive Communication (RO-MAN)</u></font>](https://ieeexplore.ieee.org/abstract/document/9223550)
<br><br><br><br><br><br>

---
**References**  

<a name="reference_1"><font size="2em" color="gray">1.</font></a> [<font size="2em"><u>The Effects of Organism- Versus Object-Based Robot Design Approaches on the Consumer Acceptance of Domestic Robots</u></font>](https://link.springer.com/article/10.1007/s12369-016-0388-1)<font size="2em">(2017) by Sonya S. Kwak, Jun San Kim and Jung Ju Choi in International Journal of Social Robotics</font> [↩](#R01)

<br>

**Footnotes**  

<a name="footnote_1"><font size="2em" color="MediumSeaGreen">1.</font></a> [<font size="2em"><u>ROGNAN robotic furniture for small space living</u></font>](https://ikea.today/rognan-robotic-furniture-for-small-space-living/) [↩](#F01)  

<br><br><br>

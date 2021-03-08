---
layout: project
permalink: /:title/
category: main

meta:
  keywords: "HRI, Social Robot"

project:
  title: "First Things First"
  subtitle: "A Survey Exploring the Key Services and Functions of a Robot"
  type: "Human-Robot Interaction (HRI)"
  logo: "/assets/images/projects/first_things_first/logo.png"
  duration: "2019.09 (1개월)"
  ptype: "Human-Robot Interaction 연구 프로젝트"
  typedetail: "KIST AIㆍ로봇연구소 지능로봇연구단"
  role: "프로젝트 기획, 시나리오 디자인, 사용자 조사"
  supporter1: "Dr. Dahyun Kang (KIST): 프로젝트 기획, 시나리오 디자인, 사용자 조사, 데이터 분석"
  supporter2: "Dr. Sonya S. Kwak (KIST): 프로젝트 지도"
  tools: "Google Forms"
  output: "ACM/IEEE HRI 2020 학회 LBR"

images:
  - image:
    url: "/assets/images/projects/first_things_first/main.png"
    alt:

---
---
<br>

<p align="center">
  <img src="/assets/images/projects/first_things_first/intro.png">
  <br>
  <font size="2em" color="gray">가사노동을 돕는 다양한 로봇들이 개발되고 있다.</font>
</p>  
<br><br>

<font size="6em">Background</font>
<br>

Design Question: "앞으로 개발되어야 하는 <span style="background-color:#EBEBEB">홈 로봇 서비스</span>는 어떻게 디자인될 수 있을까?"  
<br><br>

<span style="background-color:#EBEBEB">가사노동</span>은 대부분의 사람들이 하기를 꺼려 하는 일이다.
다행히도, 이런 가사노동을 돕는 다양한 <span style="background-color:#EBEBEB">로봇</span>들이 개발되고 있다 (PR2<sup id="F01">[<span style="color:MediumSeaGreen">1</span>](#footnote_1)</sup>, Aeolus<sup id="F02">[<span style="color:MediumSeaGreen">2</span>](#footnote_2)</sup>, Blue<sup id="F03">[<span style="color:MediumSeaGreen">3</span>](#footnote_3)</sup>).
계속해서 가사노동은 로봇으로 대체될 것으로 예상된다<sup id="R01">[<span style="color:gray">1</span>](#reference_1)</sup>.  
<br>

우리는 <span style="background-color:#EBEBEB">가사노동</span>을 다음과 같이 정의했다.

01. 일상적으로 반복됨
02. 시장에서 거래되지 않음
03. 무보수
04. 집 안에서 일어남  
<br>

Bugmann과 Copleston의 연구에 따르면, 사람들이 로봇에게 맡기고 싶어하는 주요 가사노동은 다음과 같다<sup id="R02">[<span style="color:gray">2</span>](#reference_2)</sup>.

01. <span style="background-color:#EBEBEB">청소</span> (일반 청소, 진공 청소, 정리 등)
02. <span style="background-color:#EBEBEB">요리</span> (아침 준비, 점심 준비, 음료 만들기 등)
03. <span style="background-color:#EBEBEB">세탁</span>

<br>
<p align="center">
  <img src="/assets/images/projects/first_things_first/bg.png">
</p>  
<br><br><br><br><br><br>

<font size="6em">Goal</font>
<br>

홈 로봇의 서비스를 개발하기 위해, 가사노동 중 <span style="background-color:#EBEBEB">청소</span>, <span style="background-color:#EBEBEB">세탁</span>, <span style="background-color:#EBEBEB">요리</span>를 선택하였다.  
<br><br>

<font size="5em">1) Research Question</font>
<br>

"<span style="background-color:#EBEBEB">우선순위</span>로 개발되어야 하는 홈 로봇 서비스는 무엇인가?"
<br><br><br>

<font size="5em">2) Research Design</font>
<br>

홈 로봇 서비스의 청소, 세탁, 요리 <span style="background-color:#EBEBEB">시나리오</span>를 만들고, 사용자의 <span style="background-color:#EBEBEB">인식</span>을 평가한다.

<br>

<br><br><br><br><br><br>

<font size="6em">Study Design</font>
<br>

<font size="5em">1) Stimuli</font>
<br>

사람들이 가장 많이 사용하고 싶은 로봇의 서비스를 찾기 위해 각각 5~6 가지 기능을 포함하는 세 가지 서비스에 대한 설명을 제공했다.  
<br>

<font size="4em">1.1) Cleaning</font>
01. 공기 청정기가 로봇에게 거실 청소를 요청하면 로봇은 창문을 열어 환기를 시킬 수 있다.
02. 로봇은 책, 컵, 쿠션과 같은 물건을 적절한 위치로 되돌릴 수 있다. (1-1)
03. 로봇은 로봇청소기(진공, 물걸레 등)의 청소 시작을 명령 내릴 수 있다. (1-2)
04. 로봇은 재활용을 위해 쓰레기통에서 캔, 유리, 플라스틱 등을 분류할 수 있다. (1-3)
05. 청소가 완료되면 로봇은 환기를 위해 열린 창문을 닫고 청소 작업을 종료할 수 있다.  
<p align="center">
  <img src="/assets/images/projects/first_things_first/sd1.png">
</p>
<br><br>

<font size="4em">1.2) Laundry</font>
01. 세탁물 바구니에 세탁물이 가득 차 있음을 알리면 로봇이 세탁 바구니를 세탁기로 옮긴다. (2-1)
02. 로봇은 바구니에서 세탁물을 집어 세탁기에 넣을 수 있다.
03. 로봇은 세탁기와 건조기에게 명령을 내려서 세탁물을 세탁하고 말릴 수 있다. (2-2)
04. 세탁 및 건조가 완료되면 로봇이 세탁물을 수거 할 수 있다.
05. 로봇은 세탁물을 접을 수 있다. (2-3)
<p align="center">
  <img src="/assets/images/projects/first_things_first/sd2.png">
</p>
<br><br>

<font size="4em">1.3) Cooking</font>
01. 로봇은 냉장고의 재료를 정리할 수 있다.
02. 남은 재료와 과거 식사를 고려하여 로봇이 식사 메뉴를 추천할 수 있다. (3-1)
03. 사용자가 요리를 할 때, 로봇은 재료, 조미료 및 요리 도구를 전달하여 도울 수 있다. (3-2)
04. 로봇은 냄비 나 그릇을 테이블로 옮길 수 있다. (3-3)
05. 식사 후, 로봇은 빈 접시를 식기세척기로 옮길 수 있다.
06. 로봇은 식기세척기에 설거지를 명령 내릴 수 있다.
<p align="center">
  <img src="/assets/images/projects/first_things_first/sd3.png">
</p>
<br><br><br>

<font size="5em">2) Measures</font>
<br>

로봇의 서비스 시나리오에 따라서 아래 2가지를 측정하였다. 측정을 통해, 사용자가 각 시나리오의 로봇의 서비스에 얼마나 <span style="background-color:#EBEBEB">만족</span>하는지, <span style="background-color:#EBEBEB">구매 의도</span>가 얼마나 있는지 확인하였다.  

01. <span style="background-color:#EBEBEB">서비스 평가</span>(service evaluation)<sup id="R03">[<span style="color:gray">3</span>](#reference_3)</sup>
02. <span style="background-color:#EBEBEB">구매 의도</span>(purchase intention)<sup id="R04">[<span style="color:gray">4</span>](#reference_4)</sup>  

<p align="center">
  <img src="/assets/images/projects/first_things_first/sd4.png">
</p>
<br><br>

또한, 서비스 평가 및 구매의도에 영향을 미치는 로봇의 <span style="background-color:#EBEBEB">속성</span>(attribute)과 <span style="background-color:#EBEBEB">작업</span>(task)을 조사하기 위해 다음 항목을 평가했다.  
<br>

<p align="center">
  <img src="/assets/images/projects/first_things_first/sd5.png">
</p>
<br><br>

<font size="5em">3) Recruitment</font>
<br>

<span style="background-color:#EBEBEB">설문지 평가</span>로 진행되었으며, <span style="background-color:#EBEBEB">집단내 설계(within design)</span>하였다.
01. <span style="background-color:#EBEBEB">로봇이 제공하는 서비스</span>: within design - 피실험자는 로봇이 제공하는 청소, 세탁, 요리 등 <span style="background-color:#EBEBEB">3가지 서비스</span>를 모두 평가한다. (무작위 순서)  

피실험자: 36명 (25세~42세, 여성 24명, 남성 12명)
<br><br>

<br><br><br><br><br><br>

<font size="6em">Results</font>
<br>

실험을 통해 모듈형 스마트 스피커의 발화와 촉각이 사용자의 인식에 미치는 영향을 조사하기 위해 <span style="background-color:#EBEBEB">일원 반복측정 분산분석(one-way RM ANOVA)</span>, <span style="background-color:#EBEBEB">Tukey HSD 사후 검정(Tukey HSD post hoc test)</span>과 <span style="background-color:#EBEBEB">다중 회귀분석(multiple regression)</span>을 수행했다.  
<br><br>

<font size="5em">1) Service Evaluation by Service Types</font>
<br>

로봇 서비스 유형의 <span style="background-color:#EBEBEB">서비스 평가</span> 측정은 <span style="background-color:#EBEBEB">Cronbach α=.977</span>로, 모든 문항에 대해 <span style="background-color:#EBEBEB">유의</span>한 결과가 나왔다.  
<br>
<span style="background-color:#EBEBEB">서비스 유형</span>에 따라 <span style="background-color:#EBEBEB">서비스 평가</span>에 유의한 영향이 있었다. <font size="2em">(<i>F</i><sub>(2,107)</sub> = 3.391, <i>p</i> = 0.037)</font>.

01. 세 서비스 중 <span style="background-color:#EBEBEB">세탁</span> <font size="2em">(<i>M</i> = 6.60, <i>SD</i> = 0.74)</font>은 청소 <font size="2em">(<i>M</i> = 6.50, <i>SD</i> = 0.88)</font>와 요리  >M</i> = 6.06, <i>SD</i> = 1.13)</font>에 비해 <span style="background-color:#EBEBEB">가장 긍정적인 서비스</span>로 평가되었다.
02. Tukey HSD 사후 검정은 <span style="background-color:#EBEBEB">세탁과 요리</span><font size="2em">(<i>p</i> = 0.042)</font> 간에 <span style="background-color:#EBEBEB">유의한 차이</span>를 보였지만 청소와 세탁<font size="2em">(<i>p</i> = 0.888)</font>, 청소와 요리<font size="2em">(<i>p</i> = 0.121)</font> 간에는 차이가 없었다.
<br><br>

<font size="5em">2) Cleaning</font>
<br>

청소 서비스 측면에서는 로봇의 <span style="background-color:#EBEBEB">AI 수준</span>과 작업의 <span style="background-color:#EBEBEB">오염 수준</span>, <span style="background-color:#EBEBEB">난이도</span>가 <span style="background-color:#EBEBEB">서비스 평가</span>에 영향을 미쳤다. 작업의 <span style="background-color:#EBEBEB">오염 수준</span>과 <span style="background-color:#EBEBEB">난이도</span>는 <span style="background-color:#EBEBEB">구매 의도</span>에 영향을 미쳤다.  
<br>

<p align="center">
  <img src="/assets/images/projects/first_things_first/sd6.png">
</p>  
<br><br>

<font size="5em">3) Laundry</font>
<br>

세탁 서비스 측면에서는 작업의 <span style="background-color:#EBEBEB">난이도</span>가 <span style="background-color:#EBEBEB">서비스 평가</span>에 영향을 미쳤다. 로봇의 <span style="background-color:#EBEBEB">조종 수준</span>과 작업의 <span style="background-color:#EBEBEB">난이도</span>는 <span style="background-color:#EBEBEB">구매 의도</span>에 영향을 미쳤다.  
<br>

<p align="center">
  <img src="/assets/images/projects/first_things_first/sd7.png">
</p>  
<br><br>

<font size="5em">4) Cooking</font>
<br>

요리 서비스 측면에서는 로봇의 <span style="background-color:#EBEBEB">AI 수준</span>과 작업의 <span style="background-color:#EBEBEB">오염 수준</span>, <span style="background-color:#EBEBEB">난이도</span>가 <span style="background-color:#EBEBEB">서비스 평가</span>에 영향을 미쳤다. 작업의 <span style="background-color:#EBEBEB">위험도</span>와 <span style="background-color:#EBEBEB">난이도</span>는 <span style="background-color:#EBEBEB">구매 의도</span>에 영향을 미쳤다.  
<br>

<p align="center">
  <img src="/assets/images/projects/first_things_first/sd8.png">
</p>  
<br><br><br><br><br><br>

<font size="6em">Video Link</font>
<br>

<p align="center">
  <a href="https://youtu.be/faVdcVmok_o">
  <img src="/assets/images/projects/first_things_first/video.png">
  </a>
</p>  
<br><br><br><br><br><br>

<font size="6em">Publication</font>
<br>

[<u>First Things First: A Survey Exploring Key Services and Functions of a Robot</u> <br> <font size="2em"><u>2020 ACM/IEEE International Conference on Human-Robot Interaction(HRI) LBR</u></font>](https://dl.acm.org/doi/10.1145/3371382.3378317)
<br><br><br><br><br><br>

---  
**References**  

<a name="reference_1"><font size="2em" color="gray">1.</font></a> [<font size="2em"><u>Executive Summary World Robotics 2018 Service Robots</u></font>](https://ifr.org/downloads/press2018/Executive_Summary_WR_Service_Robots_2018.pdf) [↩](#R01)  
<a name="reference_2"><font size="2em" color="gray">2.</font></a> [<font size="2em"><u>What Can a Personal Robot Do for You?</u></font>](https://link.springer.com/chapter/10.1007/978-3-642-23232-9_32) <font size="2em">(2011) by Guido Bugmann and Simon N. Copleston in Towards Autonomous Robotic Systems (TAROS)</font> [↩](#R02)  
<a name="reference_3"><font size="2em" color="gray">3.</font></a> [<font size="2em"><u>Gracefully Mitigating Breakdowns in Robotic Services</u></font>](https://ieeexplore.ieee.org/abstract/document/5453195) <font size="2em">(2010) by Min Kyung Lee, Sara Kiesler, Jodi Forlizzi, Siddhartha Srinivasa and Paul Rybski in ACM/IEEE HRI</font> [↩](#R03)  
<a name="reference_4"><font size="2em" color="gray">4.</font></a> [<font size="2em"><u>Mental Simulation and Product Evaluation: The Affective and Cognitive Dimensions of Process versus Outcome Simulation</u></font>](https://journals.sagepub.com/doi/abs/10.1509/jmkr.48.5.827) <font size="2em">(2011) by Min Zhao, Steve Hoeffler and Gal Zauberman in Journal of Marketing Research</font> [↩](#R04)  

<br>

**Footnotes**  

<a name="footnote_1"><font size="2em" color="MediumSeaGreen">1.</font></a> <font size="2em">PR2: </font>[<font size="2em"><u>https://robots.ieee.org/robots/pr2/</u></font>](https://robots.ieee.org/robots/pr2/) [↩](#F01)  
<a name="footnote_2"><font size="2em" color="MediumSeaGreen">2.</font></a> <font size="2em">Aeolus: </font>[<font size="2em"><u>https://aeolusbot.com</u></font>](https://aeolusbot.com) [↩](#F02)  
<a name="footnote_3"><font size="2em" color="MediumSeaGreen">3.</font></a> <font size="2em">Blue: </font>[<font size="2em"><u>https://rll.berkeley.edu/blue/</u></font>](https://rll.berkeley.edu/blue/) [↩](#F03)  
<br><br><br>

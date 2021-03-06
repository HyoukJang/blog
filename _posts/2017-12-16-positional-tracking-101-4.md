---

published: true
layout: post
title: "포지셔널 트래킹 101 - 4강. 'PLS(Polarized Light Sensing) 기술과 실내 측위"
author: JH
categories: VR Indoor-positioning IPS
tags:  VR tech polariant virtual-reality positional-tracking 측위

---

지난 3강까지 측위의 개념부터 과학적 직관을 통해 알아본 원리 그리고 구체적인 방식의 종류까지 훑어보았다.

  * [포지셔널 트래킹 101 - 1강. '측위가 뭐임?']({{site.baseurl}}/vr/indoor-positioning/ips/2016/09/10/positional-tracking-101-1.html)
  * [포지셔널 트래킹 101 - 2강. '실내 무선 측위기술'의 원리]({{site.baseurl}}/vr/indoor-positioning/ips/2017/10/22/positional-tracking-101-2.html)
  * [포지셔널 트래킹 101 - 3강. '실내 무선 측위기술'의 방식]({{site.baseurl}}/vr/indoor-positioning/ips/2017/12/10/positional-tracking-101-3.html)


이번 시간에는 실내 측위 솔루션에 새로운 접근이자 필자가 창업한 스타트업인 '폴라리언트'의 보유 기술인 PLS(Polarized Light Sensing) 기술에 대해 알아보자.

![PLS_principle]({{site.baseurl}}/images/pls_1.png)

PLS 기술은 '사막개미의 귀소기작'으로부터 모티브를 얻었다. 사막개미는 모래더미로 둘러쌓인 집에서 먹이를 찾으러 100m - 200m 가량을 외출한다. 낮에는 태양빛의 뜨거움으로 페로몬은 날아가고 바람에 의해서 모래 더미의 지형이 뒤바뀌는 사막의 특성상 집을 정확히 찾아오기란 여간 쉬운게 아니다. (본인이 개미가 되었다고 생각해보자 ㅎ)

그럼에도 불구하고 정확히 집을 찾아오는 사막개미를 과학자들이 관찰해보니 태양빛이 대기에 부딪힘에 따라 일어나는 편광 패턴을 사막개미의 겹눈에서 인식하여 찾아온다는 놀라운 사실을 발견해낼 수 있었다. 우리 기술은 이에 모티브를 얻어 편광된 조명만으로도 마치 실내의 GPS 처럼 정밀 위치인식을 할 수 있지 않을까 하는 지적 호기심에서 시작되었다. 결론적으로, 위의 그림처럼 편광 필름을 일반 LED에 덧대어 만든 편광 조명 하에서 추적하고자하는 물체에 PLS 센서를 부착되어있다면 굉장히 정밀한 3차원 위치인식을 할 수 있는 기술인 것이다.

PLS 기술의 특징을 살펴보자.

1. 단 1개의 신호원(signal source)으로 동작
  * LED와 편광필터 만으로 구성된 신호원
  * 기존 무선신호는 3개 이상의 신호원이 필요했으나 LOS(line-of-sight) 상황에서 1개의 신호원만으로도 동작

2. 센서부(sensor part) 수광시 실시간 계산 방식
  * 센서부에서 최종 위치 값 계산이 완료
  * 신호원 아래에 아무리 많은 센서가 있어도 각각이 위치를 계산하여 알고 있는 높은 확장성

3. 센서부에서 모든 계산이 끝나는 작은 요구연산량
  * 카메라 비젼(vision) 추적 방식에 비해 10000배 이상 작은 연산량
  * 센서부 내부 작은 MCU에서 끝나는 연산

1개의 신호원에서 신호가 도달하는 범위내에서 수많은 센서들의 위치를 각각 정밀하게 알 수 있다면 기존에 어려웠던 일들이 가능해진다. 로봇청소기로 대표되는 사람 곁의 서비스 로봇들이 앞으로 점차 확대되면서 사람의 손이 닿지 않거나 사람이 잠자고 있을 시간에도 우리에게 도움을 주는 실내 자율주행 로봇들이 많아지면 이들의 제어에 가장 기본적인 기능이 '위치 인식'일 테다.

{% include youtube_player.html id="DCPtMLuOt8Y" %}

마치, GPS가 도로 위 자동차 네비게이션이라는 킬러앱(killer app)을 가능케 한 것처럼 우리 기술은 '실내의 GPS'로 성장해내가면서 다양한 서비스와 연계될 가능성을 충분히 지닌다.

다음 시간에는 우리 기술과 비슷한 역할을 하는 기존의 기술 대비 장점 그리고 보완재로서의 역할 등을 좀 더 자세히 다루어보도록 하겠다.

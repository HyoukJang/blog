---
published: false
layout: post
title: ' 중앙을 차지하거나 엣지를 먹거나 < NVIDIA의 미래는 어디에 > (2)'
author: JH
categories: Insight
tags: NVIDIA Google Stadia TPU
open: false
---

지난 포스트로부터 우리는 AI 하드웨어의 용처에 따른 분류 및 쓰이는 시점에 따른 주요 성능 지표에 대해 이야기를 나누었다. 

[중앙을 차지하거나 엣지를 먹거나 < AI 하드웨어 개괄> (1)]({{site.baseurl}}/insight/2019/03/24/Central-Decentral.html)

이번 포스트에서는 AI 하드웨어의 쌍두마차라고 볼 수 있는 NVIDIA와 Google의 전략 및 실행 그리고 어떤 전략이 더 유효할 것인지 가늠해보고자 한다. 일단 회사의 개괄을 알기 위하여 NVIDIA와 Google(Alphabet)의 최근 주가를 확인해 보자. 둘다 NASDAQ에 상장한 회사이므로 손쉽게 확인할 수 있다.

![Google(Alphabet)]({{site.baseurl}}/images/alphabet-stock.png){: width="400" height="400"}
![NVIDIA]({{site.baseurl}}/images/nvidia-stock.png){: width="400" height="400"}


회사 규모의 측면에서는 Google과 NVIDIA는 10배 이상 차이가 나므로 비교가 사실상 무의미하고 각 회사의 주가 흐름을 통해서 회사의 주력 비즈니스의 현황 정도는 엿볼 수 있다. NVIDIA는 익히 알고있듯이 2018년 하반기 암호화폐 시장의 급락으로 인해 채굴용 GPU의 수요가 급감하면서 주가가 반토막 나버렸다. AI 시대의 첨병으로 GPGPU 기반의 컴퓨팅 패러다임을 가장 앞서서 가져오면서 딥러닝의 등장과 함께 뜨겁게 떠올랐는데 결국 GPU 하드웨어가 타겟 디바이스에 탑재되어야 매출로 이어지는 구조로 인해 엣지 단의 고성능 컴퓨팅 수요가 감소하면 자연스레 타격을 받을 수 밖에 없었다.

딥러닝 등장 이후 암호화폐, VR/AR 등의 필요 연산 집적도가 높은 시장이 출현하기 전에는 NVIDIA의 주력 시장 타겟은 바로 게이밍 워크스테이션이었다. 그래픽스 카드라는 이름처럼 고성능의 그래픽스 정보를 처리해야하는 게임 사양에 맞추어진 게이밍 PC를 적극지원하면서 시장을 넓혀갔었고 우리나라에서도 PC방의 급격한 보급에 따라 일반인들에게 이름이 알려진 정도였다.

암호화폐, VR/AR 등 필요 연산 집적도가 높은 시장의 성장속도에 영향을 받을 수 밖에 없는 NVIDIA는 생각보다 지지부지한 시장 탓에 직격탄을 맞으며 고전을 하고 있지만 최근에는 주요 차량 제조사들과 자율주행 테마에 맞춘 제품군을 공격적으로 출시하고 있다. 과연 NVIDIA의 미래는 어떻게 될까?

나는 현재 스코어 기준으로는 부정적이다. 그 사유는 다음과 같다.

(1) 차량 메이커와의 협업은 모빌리티의 헤게모니 싸움에서 불리
(2) 데이터 센터 시장에서 미진한 존재감
(3) 스트리밍 게이밍 시장의 대두와 게이밍 워크스테이션 및 PC 시장 점유율 축소








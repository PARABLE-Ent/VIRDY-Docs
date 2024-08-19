---
description: 'Xsens 세팅'
sidebar_label: 'Xsens 세팅'
sidebar_position: 6
---

# Xsens 세팅

## Network Streamer 설정
![xsens1](/img/Page_AvatarSettings/MotionSet/xsens_1.png) <br/>
MVN 소프트웨어 상단의 <span class="highlight_text">**Network Streamer**</span>를 클릭합니다.

:::caution Network Streamer가 안보여요 !
MVN 소프트웨어에서 Network Streamer가 안보이는 경우 **Xsens License**가 활성화 되지 않아 생긴 문제입니다. <br/>
**Xsens License**가 정상적으로 활성화 되었는지, **구독 기간**이 종료되지는 않았는지 확인하시기 바랍니다.
:::

<br/>

![xsens2](/img/Page_AvatarSettings/MotionSet/xsens_2.png) <br/>
이미지와 같이 설정합니다. 일반적으로 Add 버튼 클릭시 생성되는 **기본값**을 그대로 사용합니다.

:::tip Host IP
VIRDY와 MVN 소프트웨어를 같은 PC에서 실행시 Host는 **```127.0.0.1```** 으로 설정합니다. <br/>
서로 다른 PC로 실행시 **VIRDY가 실행된 PC의 IP**를 입력해주세요.
:::

<br/>

## VIRDY - Xsens 활성화

![xsens3](/img/Page_AvatarSettings/MotionSet/xsens_3.png) <br/>
모션 트래킹 탭에서 Xsens를 선택, **활성화**를 해줍니다. <br/>
액터 ID는 기본값 ```1```로 설정합니다.

## Xsens 다인 연결

![xsens4](/img/Page_AvatarSettings/MotionSet/xsens_4.png) <br/>
Xsens는 1대의 PC에서 최대 4인까지 연결이 가능합니다. <br/>
MVN 소프트웨어에서 세팅시 첫번째 액터가 **액터 ID 1**, 그 다음 액터는 **액터 ID 2**로 자동 구분됩니다.


![xsens5](/img/Page_AvatarSettings/MotionSet/xsens_5.png) <br/>
다인 세팅시 <span class="highlight_text">**VIRDY 액터**</span> 또한 추가하여 순서에 맞게 Xsens 액터 ID를 부여합니다.
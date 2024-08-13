---
description: 'VIRDY 아바타 업로드 및 트래킹 설정'
sidebar_label: '아바타 및 트래킹 설정'
sidebar_position: 2
---

# 아바타 설정

## 액터 추가 및 아바타 업로드
![AvatarSetImage1](/img/Page_AvatarSettings/1.png) <br/>
VIRDY는 사용자의 캐릭터를 <span class="highlight_text">**액터**</span>라 칭하고 있습니다. <br/>
최초 접속시 액터를 생성하여야 합니다. 생성된 액터는 <span class="highlight_text">**상단 탭**</span>에 구분됩니다.

![AvatarSetImage2](/img/Page_AvatarSettings/2.png) <br/>
우측 하단 <span class="highlight_text">**액터 창**</span>을 클릭하면 아바타를 업로드하고 관리할 수 있는 창이 생성됩니다. <br/>
아래 아바타 추가 버튼을 눌러 **``vrm``** 혹은 **``vsf``** 파일을 업로드 해주세요.

![AvatarSetImage3](/img/Page_AvatarSettings/3.png) <br/>
아바타 업로드가 완료되면 우측 패널에 <span class="highlight_text">**카드 형태**</span>로 저장됩니다. <br/>
아바타 카드를 선택하여 사용하고자 하는 대표 아바타를 설정해주세요.

![AvatarSetImage4](/img/Page_AvatarSettings/4.png) <br/>
액터의 이름을 설정할 수 있습니다. <br/>
월드 접속 후에는 액터 이름이 함께 표기되기에 별도 이름을 지정해주시는 편이 좋습니다.

![AvatarSetImage5](/img/Page_AvatarSettings/5.png) <br/>
좌측 하단 <span class="highlight_text">**페이셜 트래킹, 모션 트래킹**</span> 버튼을 눌러 <br/> 바디 / 페이셜 트래킹을 설정할 수 있습니다.

## 페이셜 트래킹 설정
![AvatarSetImage6](/img/Page_AvatarSettings/6.png) <br/>
총 4개의 단락으로 이루어지며, 연결 방법은 일반적인 버추얼 프로그램들과 동일합니다.

**1.** <span class="highlight_text">**활성화**</span>를 <span class="highlight_text">**On**</span>으로 변경합니다. <br/>
**2.** 사용할 <span class="highlight_text">**iPhone과 PC**</span>를 같은 네트워크로 연결합니다. <br/>
**3.** iPhone의 IP 주소를 <span class="highlight_text">**디바이스 아이피 주소**</span>에 입력하거나, <span class="highlight_text">**페이셜 앱에 PC IP**</span>를 입력합니다. <br/>
**4.** 포트를 <span class="highlight_text">**페이셜 앱의 포트 넘버**</span>와 동일하게 설정합니다. <br/>

:::caution 정상적으로 세팅했는데 연결이 안돼요 !

위 과정을 정상적으로 진행했음에도 페이셜 연결이 안되었다면, <br/>
VIRDY 프로그램의 <span class="highlight_text">**방화벽을 허용**</span>하여야 합니다.

![AvatarSetImage7](/img/Page_AvatarSettings/7.png) <br/>
윈도우 검색창에서 <span class="highlight_text">**'Windows 방화벽에서 앱 허용'**</span>을 입력 후 실행합니다. <br/>
<span class="highlight_text">**'설정 변경'**</span>을 클릭 후 <span class="highlight_text">**'virdy'**</span>를 찾아 전부 활성화 해주세요.

:::

## 모션 트래킹 설정

![AvatarSettingsImage8](/img/Page_AvatarSettings/8.png) <br/>
하단 모션 트래킹 버튼을 클릭하여 <span class="highlight_text">**모션 트래킹 설정창**</span>을 활성화합니다. <br/>
설정 방법은 <span class="highlight_text">**페이셜 트래킹과 동일**</span>합니다.

:::caution CAUTION !
현재 **``0.9.2``** 버전에서는 **SteamVR** 설정이 지원되지 않습니다. (추후 업데이트 예정) <br/>
**SteamVR**에서 지원되는 장비를 사용하시는 경우 <a href="https://protocol.vmc.info/" class="custom-link" target="_blank_" >**VMC 프로그램**</a>을 이용하시기 바랍니다.
:::

## 트래킹 세부 설정

![AvatarSettingsImage9](/img/Page_AvatarSettings/9.png) <br/>
우측 하단 <span class="highlight_text">**트래킹 세부 설정**</span> 탭은 모션 데이터의 세부 옵션을 조절할 수 있습니다.
- **거울모드**
  - 모션 데이터를 반전시켜 적용합니다.
- **모션 보간**
  - 값이 높을 수록 모션이 천천히 따라 움직이고, 낮을 수록 지연 시간 없이 적용됩니다. <br/> 트래커의 떨림이 심하거나 부드럽지 않을 때 적절히 조절하면 좋습니다.
- **모션 강도**
  - 모션 움직임의 스케일을 조절합니다.
  - 값을 높이면 작은 움직임도 크게 반응하며, 값이 낮아질 수록 실제 움직임보다 더 적은 범위로 움직입니다.

### 페이셜 민감도
- **눈동자 움직임 강도**
  - 페이셜 눈동자 움직임의 스케일을 조절합니다. 모션 강도와 동일한 기능의 옵션입니다.
- **눈썹 움직임 강도**
  - 페이셜 눈썹 움직임의 스케일을 조절합니다. 모션 강도와 동일한 기능의 옵션입니다.
- **입/볼 움직임 강도**
  - 페이셜 입/볼 움직임의 스케일을 조절합니다. 모션 강도와 동일한 기능의 옵션입니다.

### 헤드 트래킹
- **팔 각도**
  - 페이셜 헤드 트래킹 시 아바타의 팔 각도를 조절하는 기능입니다.
- **어깨 고정도**
  - 페이셜 헤드 트래킹 시 어깨 움직임의 고정도를 조절합니다.
- **몸 고정도**
  - 페이셜 헤드 트래킹 시 몸 움직임의 고정도를 조절합니다.
- **목 고정도**
  - 페이셜 헤드 트래킹 시 목 움직임의 고정도를 조절합니다.

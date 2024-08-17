---
description: 'VIRDY SDK 설명 및 사용 방법'
sidebar_label: 'SDK 개요'
sidebar_position: 1
---

# VIRDY SDK 개요

:::tip
**VIRDY 월드**에서 사용되는 대부분의 기능은 **SDK** 형태로 배포중입니다. <br/>
SDK 패키지는 **패러블 담당 매니저** 혹은 **...** 으로 문의 부탁드립니다.
:::

### 설치 방법

<span class="highlight_text">**VIRDY SDK**</span>는 <strong>```git URL```</strong>을 통해 설치할 수 있습니다. <br/>
**``'https://...'``** 해당 링크를 Unity Pacakge Manager -> + 버튼 -> 'Add package from git URL...'에 입력하여 설치해주세요. 
- 아래 사진 첨부

### 사전설치 패키지

SDK에 <span class="highlight_text">**유니티 Registry 패키지**</span>를 사용하는 스크립트가 있습니다. 각 패키지를 설치하지 않으면 <span class="highlight">**컴파일 에러**</span>가 발생합니다. <br/> <br/>
VIRDY는 기본적으로 아래 유니티 Registry 패키지를 설치하는걸 추천드리지만 만약 용량상 설치가 어려울 경우, <br/> 컴파일 에러를 발생시키는 SDK 스크립트를 삭제해주세요.

- **```Visual Effect Graph```**
- **```Cinemachine```**
- **```TextMeshPro```**

### 사용 가능 C# 스크립트 에셋

VIRDY에서 사용 가능한 에셋입니다. VIRDY의 월드 빌드 환경에서는 <span class="highlight_text">**프로그램과 월드가 동일한 스크립트**</span>를 보유하여야 합니다. <br/>
현재 VIRDY에서는 아래 에셋들을 지원하고 있습니다.

<details>
<summary>**월드 에셋**</summary>
<div markdown="1">

- **```Volumetric Lights```**
- **```Volumetric Light Beam```**
- **```Volumetric Fog 2```**
- **```KWS Water```**
- **```Atmospheric Height Fog```**
- **```HBAO (Horizon Based Ambient Occlusion)```**
- **```Planar Reflections 4```**
- **```ShinySSRR```**
- **```Water Caustics Effect for URP v2```**
- **```DOTweenPro```**

</div>
</details>

<details>
<summary>**아바타 에셋**</summary>
<div markdown="1">

- **```Magaica 1```**
- **```Magaica 2```**
- **```Dynamic Bone```**
- **```VRM Spring Bone```**

</div>
</details>


:::tip
월드 혹은 아바타에 직**접 작성한 C# 스크립트**를 사용하길 원하시면 <br/>
**패러블 담당 매니저** 혹은 **...** 으로 문의 바랍니다.
:::
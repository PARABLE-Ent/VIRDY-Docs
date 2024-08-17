---
description: 'VIRDY SDK - Local & Global 설명'
sidebar_label: 'SDK - Local & Global'
sidebar_position: 2
---

# SDK - Local & Global

월드 내에서 사용되는 기능들은 Local 혹은 Global로 사용됩니다.

- **Local**
  - Local은 조작하는 사용자에게만 적용됩니다.
  - 월드 내의 기능이 많아 UI를 On/Off 하거나 개인 최적화를 위한 용도로 사용됩니다.
- **Global**
  - Global은 월드 내 모든 유저에게 적용됩니다.
  - **```GlobalFunction```** 스크립트를 사용하여 설정할 수 있습니다.

GlobalFunction 스크립트를 

:::tip
**```GlobalFunction```** 으로 연결된 기능들은 서버로 호출, 그리고 서버에서 모든 유저에게 다시 호출하는 형태로 구성됩니다. <br/>
:::
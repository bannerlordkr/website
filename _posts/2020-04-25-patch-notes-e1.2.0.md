---
layout: post
style: post
categories: news patchnote
thumbnail: https://steamcdn-a.akamaihd.net/steamcommunity/public/images/clans/26623866/758b1566e26eb207d918dd46963499ec35c38cc5.png
title: 패치 노트 e1.2.0 & 베타 e1.3.0
date: 2020-04-25 00:00:00 +0900
author: Google Translate
source: https://steamcommunity.com/games/261550/announcements/detail/2199388922822905488
comments: true
---

Calradia의 전사들!  
오늘, 우리는 현재 베타 브랜치를 메인 스팀 브랜치로 옮깁니다. 아래에서 베타 브랜치에 포함 된 원래 변경 사항, 베타 브랜치에 대한 이전 핫픽스 및 이후에 수행 한 추가 변경 사항을 확인할 수 있습니다.  
베타 분기에 대한 업데이트도 있습니다. 이에 대한 패치 노트는 아래에서 더 찾을 수 있습니다.  

# 메인
## 버전
    네이티브: e1.2.0
    샌드박스코어: e1.2.0
    샌드박스: e1.2.0
    스토리 모드: e1.2.0
    커스텀 배틀: e1.2.0

# 최신 변경 사항 :
## 멀티 플레이어 충돌
- 플레이어 상태가 잘못되는 몇 가지 버그가 수정되었습니다. 이는 플레이어가 로그인하지 못하게 하는 문제 중 일부입니다.
- 붐비는 서버 (Siege)에 가입하는 동안 발생한 클라이언트의 충돌 문제를 해결했습니다.
- 에이전트가 무기를 떨어 뜨렸을 때 충돌이 발생하지 않도록 전용 서버의 코드를 보호했습니다 (공성).
- 드문 서버 충돌이 수정되었습니다.

## 멀티 플레이어 디자인 및 균형
- 부대 균형
    - 바 타니아
        - 클랜 전사 부대 수 20> 21 증가
        - 야만인 병력 증가 17> 18
        - 야생의 부대 수 증가 16> 17
        - 장착 된 전사의 방어력이 8> 16으로 증가했습니다.
        - 탑재 된 전사 부대 수 9> 16 증가
        - 맹세의 갑옷 증가 40> 43
    
    - 제국
        - 강의 가격 증가 130> 140
        - 팔 라틴 가드 메나 볼 리온 퍽은 올바른 메나 볼 리온을 장비합니다.
        - 신병 모집 속도가 78> 80으로 증가했습니다.
    
    - 블란 디아
        - 상사 방어력 감소 41> 37
        - 기사 가격 증가 180> 190
    
    - 스터 지아
        - 브리 건 속도 증가 75> 79
        - Varyag 가격 증가 140> 150
        - 광전사 방어력 감소 15> 6
        - 광전사 부대 수 감소 18> 17
        - 레이더 부대 수 증가 7> 9
        - Druzhinnik 가격 인상 170> 180
    
    - Aserai
        - 스커 미셔 속도 증가 78> 80

- 무기 밸런스
    - Menavlion 길이 감소 200> 179
    - 메나 볼 리온 데미지 감소 147> 129
    - 무거운 메나 볼 리온 데미지 감소 177> 166
    - 긴 메나 볼 리온 데미지 감소 149> 137

# 이전 베타 핫픽스 :
- 방패를 장착하면 AI가 차단 될 가능성이 높습니다. 일반 부대는 일반적으로 더 높은 무기 기술을 가지고 있습니다.
- 플레이어가 진영 통치자 였고 용병 또는 사소한 진영과의 계약을 끝내고 빚을 해결하지 못했을 때 발생하는 충돌을 수정했습니다.
- 임신 확률이 낮아졌습니다.
- 성능이 저하 된 AI 버그가 수정되었습니다.
- 요원이 더 이상 방어벽 형성에서 동맹 공격을 막지 않습니다.
- 멀티 플레이어 클라이언트 충돌이 수정되었습니다.
- 군주의 전당에 두 번 이상 진입했을 때 추가 경비병이 생성되던 문제를 수정했습니다.
- 사용 가능한 메모리가 적은 시스템의 충돌 전 경고 개선
- 일치하지 않는 버전으로 저장 파일을로드하려고 할 때 게임 충돌 가능성이 줄어 듭니다.
- 플레이어가 가족 불화 문제 퀘스트의 동반자를 다른 문제의 대체 솔루션으로 보낸 후 발생하는 충돌을 수정했습니다.
- 캐러밴은 그들이 포로를 잡은 포로를 팔기 시작합니다.
- AI 전투 효과가 향상되었습니다.
- 마을은 일주일 만에 파산했다. 이 문제는 해결되었습니다.

# 초기 베타 변경 내역
## 싱글 플레이어
### 충돌
- 마운트가 변경되는 동안 마운트의 라이더에 액세스하여 발생한 충돌이 수정되었습니다.
- 죄수 영웅을 실행할 때 발생하는 충돌을 수정했습니다.

### 성능
- UI에서 일부 메모리 누수를 해결하여 VRAM 사용량이 줄었습니다.
- 미션의 일부 스파이크를 수정했습니다.
- 세계지도의 사소한 GPU 메모리 사용량 감소

### 저장 & 로드
- 구 버전 저장 게임을로드 할 때 스킬 레벨이 유지됩니다.

### 언어 현지화
- 중국어 번체 추가
- 일부 문법 오류가 수정되고 일부 오타가 수정되었습니다.
- 터키어 및 중국어 간체 번역의 개선, 추가 및 수정

### 아트
- 인공 지능의 도망 포인트가 전투 지형에 추가되었습니다.
- 잘못 배치 된 텍스처를 수정하고 상점 스탠드에 더보기 좋은 요소를 추가했습니다.
- 아세라이 마을 중 하나에서 일부 시각적 문제가 수정되었습니다.
- 블란 디안 선봉대 방패 배너 문제 수정
- 식물상에 피를 렌더 할 때 나타나는 특정 시각적 결함을 수정했습니다.
- 제작을 위한 새로운 아이템 3 개 (칼 1 개, 칼날 1 개, 창 1 개)를 추가했습니다.
- 아이템 제작시 일부 문제가 해결되었습니다.

### UI
- 플레이어에게 지도 알림이 표시되지 않고지도 알림이 사라지는 버그를 수정했습니다.

### 전투와 공성전
- 적을 약탈 할 때, 아이템의 기본값이 너무 낮거나 너무 높으면 시스템이 아이템에 수정자를 제공 할 수 있습니다.
- 미사일은 이제 공성 사다리의 계단 사이를 통과 할 수 있습니다.
- 시체와 던진 바위가 그 아래의 엔티티가 파괴 된 후에 지워지지 않는 문제가 수정되었습니다.

### AI 전투
- 플레이어가 (공성 임무 중 별도의 동맹국 인) 편을 돕고 있다면 포위 AI가 예기치 않게 작동하여 충돌을 일으킬 수있는 치명적인 버그가 수정되었습니다.
- 정적에서 동적 내비 메시로 또는 그 반대로 이동할 때 AI 길 찾기가 경로를 거의 항상 재설정하는 중요한 버그로 인해 성능 문제가 발생하고 에이전트가 공성 탑을 올바르게 올라갈 수 없었던 문제가 수정되었습니다.
- 임무 행동의 순서가 잘못되면 팀의 장군이 군대 포위의 `리딩을 선택하기` 단계에서 풀렸다. 이것은 수정되었습니다.
- 포위 공격으로 램으로 외부 게이트를 깨고 내부 게이트를 공격 한 AI는 사다리를 통해 성으로 달려 가려고하여 게이트의 뒷면을 선택하여 게이트를 공격 한 사람들을 강화하기를 기다렸습니다. 버그. 이것은 수정되었습니다.
- 특히 군대가 서로 멀리 떨어져있을 때 발생하는 버그를 수정하고 퇴각 명령을 내릴 때 요원이 적을 향해 달려갔습니다.
- AI의 불필요한 경로 찾기 호출을 제거하여 특히 결정하려는 결정에 영향을 미치지 않고 포위에서 성능 문제를 발생 시켰습니다.

### 캐릭터 개발 시스템
- 스킬 XP 증가 공식이 10 + 스킬 레벨로 변경되었습니다.
- 남성에서 여성으로 전환 할 때 모든 수염 및 기타 남성 전용 속성이 재설정되는 캐릭터 생성 문제가 수정되었습니다.

### 클랜과 파티
- 동료는 이제 수정자가 포함 된 저렴한 아이템을 제공하므로 쉽게 모집 할 수 있습니다.

### 경제와 무역
- 더 높은 등급의 갑옷은 이제 마을에서 생산되며 때로는 시장에서 볼 수 있습니다.

### 제작
- 제작 된 아이템이 다른 통계를 가지고 생성 중에 표시 될 수있는 버그를 수정했습니다.
- 제작 된 아이템이 세이브 게임에서로드 될 때 통계 변경 사항을 잃는 버그를 수정했습니다.

### 정착 조치 (도시, 마을, 성 및 은신처)
- 건설 강화로 x2 건설 속도가 아닌 50 건설이 추가되었습니다.
- 동료에게 자신을 찾도록 요구하거나 마을 사람들이 우리 근처에있는 동료를 찾도록 요구하는 문제가 해결되었습니다.
- 정착 프로젝트의 완료 시간을 부정적으로 만들었던 버그를 수정했습니다.


### 퀘스트 및 이슈
- 가족 불화 퀘스트 관련 수정 / 개선
    - 버그
        - 저장 및 불러 오기 후 퀘스트 대화 상자가 사라지는 버그를 수정했습니다.
        - 대상 마을에 퀘스트 NPC가 생성되지 않던 문제를 수정했습니다.

    - 개량
        - 대화 내용을 추가 / 변경했습니다.
        - 일부 로그 항목을 추가 / 변경했습니다.
        - 플레이어가 파티에서 퀘스트 NPC를 해제하면 퀘스트는 실패합니다.

- `우리 사이의 스파이 (스파이 파티)` 퀘스트 관련 수정 / 개선
    - 일반
        - 퀘스트 제목이 `우리 사이의 스파이`로 변경되었습니다.
        - 이제부터는 퀘스트 주는 사람이 군대 안에 있더라도 퀘스트를 활성화 할 수 있습니다.

    - 수정
        - 스파이 후보자의 얼굴 키를 변경하는 버그를 수정했습니다.
        - 스파이로 결투 할 때 UI 상태 표시 줄에 플레이어에 잘못된 값이 표시되는 버그를 수정했습니다.
        - 관련된 정착지 내에서 게임을 저장하고로드 할 때 스파이 후보가 사라지는 버그를 수정했습니다.

    - 개량
        - 스파이는 플레이어의 기술에 따라 확장됩니다.
        - 스파이를 위한 더 나은 전투 장비를 추가했습니다.
        - 대화 내용을 추가 / 변경했습니다.
        - 마을 사람들이 플레이어에게 단서를 줄 수있는 무작위 화 매개 변수가 문제가되는 상황을 방지하도록 조정되었습니다.
        - 스파이 후보자를위한 시각적 추적기를 추가했습니다 (기본값 : "Alt"키).
        - 발급 기간이 35 일에서 5 일로 변경되었습니다.

- `주님은 교사가 필요합니다` 퀘스트 관련 수정 / 개선
    - 수정
        - 플레이어가 포로로 잡힌 후 퀘스트 NPC가 사라지는 버그를 수정했습니다.
        - 퀘스트 주는 사람과 퀘스트 NPC가 같은 사람이되는 버그를 수정했습니다.

    - 개량
        - 일부 로그 항목을 추가 / 변경했습니다.
        - 플레이어와 퀘스트 NPC가 분리 된 경우 플레이어는 퀘스트 로그를 통해 퀘스트 NPC를 추적하고 찾을 수 있으므로 퀘스트를 계속 진행할 수 있습니다.

- `Lord Wants Rival Captured` 퀘스트 관련 수정 / 개선
    - 수정
        - 퀘스트 주는 사람에게 열이 없으면 퀘스트가 멈추는 버그를 수정했습니다.
        - 중복 / 빈 로그 항목을 유발하는 버그가 수정되었습니다.

    - 개량
        - 플레이어가 대상 NPC를 퀘스트주는 사람에게 전달할 수있는 대화 옵션이 추가되었습니다.

- `Headman Needs Grain` 문제에 대한 사소한 수정.
- 추가 이슈 퀘스트 대화 개선.
- 설득의 매개 변수는 밀렵꾼 군대, 가족 불화 및 기타 퀘스트에서 수정되었습니다.

### 기타
- 그들의 특성에 더 잘 맞도록 작은 세력의 정밀 검사 장비.
- 우리가 두 번째로 마을에 들어 왔을 때 경비원이 실종되었습니다. 이것은 수정되었습니다.
- 적대적인 정착지에 들어갈 때 플레이어의 동반자 초상화의 색상을 수정했습니다.
- 플레이어의 형제를 조금 더 젊게 만들었습니다.
- 수감자가 총재가되는 버그를 수정했습니다.

## 멀티 플레이어
### 오디오
- 특정 이벤트에 알림 소리를 추가했습니다 (예 : 누군가 깃발을 잡을 때 먼 소리).

### 서버 및 네트워크
- 끝나는 커스텀 게임 참여 요청과 관련된 문제를 수정했습니다.
- 여러 명의 파티원이 동시에 게임에 참여하도록 요청하는 문제가 해결되었습니다.
- 로비에서 단절되는 드문 경우가 수정되었습니다.

## 공통 사항
### 성능
- 필드 전투와 공성전에서 CPU 성능이 크게 향상되었습니다.
- 멀티 코어 사용에서 약간의 성능 향상.

### 아트
- 헬멧에서 수염이 튀어 나오는 현상을 수정했습니다.

### 오디오
- 느린 HDD에서는 사운드 재생에 약간의 개선이 지연되었습니다.
- 구형 CPU의 오디오 성능 향상
- 볼더 충격음에서 클릭과 팝이 제거되었습니다.
- 주변 소리의 볼륨이 약간 변경되었습니다.


# 베타
## 버전
    네이티브: e1.3.0
    샌드박스코어: e1.3.0
    샌드박스: e1.3.0
    스토리 모드: e1.3.0
    커스텀 배틀: e1.3.0
    
## 싱글 플레이어
### 충돌
- 캠페인 맵에서 두 명의 플레이어 관련 이벤트가 동시에 시작될 때 발생하는 드문 충돌을 수정했습니다.
- 공성 준비 도중 파티가 설득 될 때 발생하는 게임 정지 문제를 해결했습니다.
- 속성 및 포커스 포인트를 최대로 설정하면 게임이 중단되는 문제를 수정했습니다.

### 성능
- 장면 로딩 시간이 크게 단축되었습니다.
- 전투 성능이 향상되었습니다.

### 언어 현지화
- 일부 텍스트의 개선, 추가 및 수정.
- 터키어 현지화 업데이트.

### 아트
- 3 개의 새로운 메뉴 배경이 추가되었습니다.
- 마을에 AI 도망 지점을 추가했습니다.
- 일부 소품 LOD가 업데이트되었습니다.
- 일부 메시 물리 문제를 수정했습니다.
- 엠파이어 선술집 장면에서 일부 문제가 수정되었습니다.
- 숲 은신처 장면에서 LOD 문제를 해결했습니다.
- 다양한 옷의 클리핑 문제를 해결했습니다.

### 애니메이션
- 낙타 라이더를 위해 캠페인 맵에 글레이브 공격 애니메이션이 추가되었습니다.
- 초기 캐릭터 제작 단계의 애니메이션 점검.

### 캠페인 지도
- 세계 지도 GPU 메모리 사용량이 줄었습니다.

### UI
- 플레이어가 파티에 참여한 영웅의 장비를 사용하여 퀘스트를 수행 할 수있는 인벤토리의 악용을 수정했습니다.
- ALT-F4로 게임을 닫을 때 발생하는 오류를 수정했습니다.
- 장면 알림 팝업, 캐릭터 개발자의 사소한 수정 및 조정.
- 인벤토리에서 비교할 수있는 아이템이 없을 때 ALT로 비교 아이템 통계를 변경하는 동안 게임이 멈추는 버그를 수정했습니다.
- 캐릭터 개발자의 특전, 전체 학습 속도 및 현재 기술 수직 지표의 고정 배치.
- 고정 할 수없는 동물에게는 고정 속도 장착 아이콘이 표시됩니다.
- SP kill-feed 및 SP 스코어 보드의 성능이 약간 향상되었습니다.
- 지도 정보 표시 줄에서 주요 당사자 상태 툴팁 형식을 수정했습니다.
- 캐릭터 개발자 화면을보다 와이드 스크린 친화적으로 만들었습니다.
- 백과 사전의 클랜 목록 페이지에 Destroyed 및 Not Destroyed 필터 옵션을 추가했습니다.
- 백과 사전 영웅 목록 페이지에 Alive / Dead 상태 필터 옵션을 추가했습니다.
- 파괴 된 클랜의 배너는 이제 백과 사전 페이지에서 채도가 낮아 보입니다.
- 저장된 게임에서 로드된 모듈 패널을 스크롤 할 수 있습니다.

### 전투와 공성전
- 시뮬레이션 전투에서 수 이점의 효과가 증가했습니다.
- 공성전 공격은 이제 시뮬레이션에서 더 오래 지속됩니다.
- 공성 돌격 시뮬레이션에서 벽 품질의 효과가 향상되었습니다.
- 전투 임무는 산란 중 에이전트의 성숙도를 확인하고 필요한 경우 나이를 늘립니다.
- 공성 탑 부착 위치에서 AI가 벽에서 떨어지 던 문제를 수정했습니다.
- 샐리 아웃 동안, 수비대는 이제 포위 수용소 지도자와 같은 진영에있는 정당 만이 아니라 합의 외부의 모든 적의 힘을 고려합니다.

### AI 전투
- 공성전에서 양쪽이 너무 약할 때 발생하는 버그를 수정했습니다. 이와 같은 경우, 더 강력한 쪽은 때때로 벽 위의 경로없이 벽으로 걸어 들어가도록 충전하려고 시도합니다.
- 궁수들이 충돌기를 사용하여 적을 볼 수 있는지 확인하는 드문 문제를 수정하여 잘못된 방향으로 향하게 할 수 있습니다.

### 캐릭터 개발 시스템
- 트레이드 스킬의 트레이드 페널티가 스킬 포인트 당 0.4 %로 증가했습니다.
- 장인 커뮤니티 및 대기업 특전의 보너스가 감소했습니다.
- 캐릭터 제작에서 문화적 위업을 구현하고 수정했습니다.
- 캐릭터 제작에서 Battanian 문화의 청소년기 옵션이 4에서 6으로 증가했습니다.
- 튜토리얼 교장과 대화하면서 많은 매력을 경험하던 버그를 수정했습니다.
- 나이 진행을 조정했습니다. 캐릭터는 나이와 비슷해 보일 것입니다.

### 클랜과 파티
- 어린이 수가 1 명 또는 2 명인 경우 임신 가능성 증가
- 영웅 임금이 더 이상 0이 아닙니다.
- 군주에는 경험이 많은 병력과 적은 인원이 있습니다. 또한 가능한 한 파티 크기 제한을 사용합니다.
- 파티는 파티 규모 제한에 도달 한 경우 패배 한 파티의 수감자를 모집하지 않습니다. 이로 인해 일부 인공 지능 파티는 황폐로 인해 더 나은 부대를 잃게되었습니다.
- 클랜 지도자의 더 나은 경제 관리로 인해 주둔지 규모가 약간 증가합니다.
- 포로의 탈출 기회는 이동 파티에있을 때 25 % 감소합니다. 플레이어가 합의하면 50 % 감소합니다.
- 클랜 지도자의 재정 상황은 이제 확률을 높이는 데 영향을 미치므로 부족한 부족은 더 많이 습격하기를 원합니다.
- 캐러밴, 주민 및 민병대 파티에는“기 부대”및“부대 검사”옵션이 비활성화되었습니다.

### 군대
- 식량이 적은 군대는 이제 적대적인 계획을 계속하고 기아로 인해 군대를 잃지 않고 정착지로 더 자주 돌아옵니다.
- 부상당한 비율이 높은 당사자와 군대는 이제 군대를 치료하기 위해 정착촌에서 휴식을 취하는 것을 선호합니다.
- 때때로 군대 멤버 파티는 군대가 도움을 줄 것이라고 가정했을 때보 다 강력한 파티를 공격하고 있었지만 군대 리더에 아직 연결되지 않았고 군대의 도움이 발생하지 않았습니다. 이 버그가 수정되었습니다.
- 합의로 향하는 동안 NPC 당사자는 때때로 자신이가는 도중에 지나가는 다른 합의를 방문하기도합니다. 이것은 더 나은 채용으로 이어집니다.
- 캐러밴에 부상당한 병력이 많으면 마을에서 회복하기 위해 더 오래 기다립니다.
- 군대가 요새를 방문하면 군대 추종자 인 플레이어는 정착 옵션을 입력하여 정착 메뉴를 열 수 있습니다.

### 경제와 무역
- 플레이어는 이제 할인 된 가격으로 물품을 캐러밴에 판매 할 수 있습니다.
- 캐러밴은 이제 섬프 말로 생성됩니다.
- 밸런스 문제로 인해 소유 캐러밴과의 플레이어 거래가 비활성화되었습니다.
- 캐러밴을 만드는 동안 플레이어는 이제 보조 옵션을 사용할 수 있습니다. 그러나 이 시나리오에서는 캐러밴 성형 비용이 1.5 배입니다.

### 제작
- 제작시 홀스터가 활성화되어있을 때 보이지 않는 무기가 수정되었습니다.

### 정착 조치 (도시, 마을, 성 및 은신처)
- 선술집에서 용병 부대의 출현 확률이 33 %에서 50 %로 증가했습니다.

### 퀘스트 & 이슈
- 헤드 맨이 무리 퀘스트를 제공해야하는 사소한 문제를 해결했습니다.
- `Notable Wants Daughter Found Quest`에서 사소한 문제를 수정하고 일부 디자인을 변경했습니다.
- 갱의 리더, 무기 퀘스트 버그 수정 및 개선 필요
    - 수정
        - 플레이어가 퀘스트를 성공적으로 완료했을 때 발생하는 충돌을 수정했습니다.
        - 플레이어가 퀘스트 경비원에 의해 잡힐 때 합의를 떠나기로 결정했을 때 발생하는 충돌을 수정했습니다.
        - 저장 및로드 후 퀘스트 로그 진행률이 재설정되는 버그가 수정되었습니다.
        - 퀘스트 가드가 플레이어의 무기를 가져갈 때 알림 버그를 수정했습니다.

    - 개량
        - 보상 금 공식이 변경되었습니다.
        - 대체 (동반자) 솔루션 기간 수식이 변경되었습니다.
        - 컴패니언 공식에 필요한 무역 / 도발 기술이 변경되었습니다.
        - 요청 된 무기 량 공식이 변경되었습니다.
        - 퀘스트 경비병 공식을 훔치는 무기 기회가 변경되었습니다.
        - 이제부터 퀘스트 가드는 플레이어를 더 자주 멈출 것입니다.
        - 퀘스트 주는 더 이상 석궁을 요구하지 않습니다.

- 플레이어가 저장 및 로드 후 `바운티 헌터에 의해 캡처 됨` 퀘스트 제공자에게 `내가 한 작업에 대해` 대화 옵션을 클릭 할 때 대화가 멈추는 문제를 수정했습니다.
- `Neretzes Folly 조사`퀘스트 진행 회귀 버그가 플레이어가 이전에 이야기했던 귀족이 죽었을 때 발생하던 버그를 수정했습니다.

### 대화와 만남
- 플레이어가 장착 된 경우, 결제 메뉴에서 "말하기"버튼을 사용할 때 대화 캐릭터에서 조금 더 튀어 나옵니다.
- 말 귀와 말 장치가 보이지 않도록지도 대화 임무 (만남)에서 말과 함께 산란을 비활성화했습니다.
- 대화가 끝난 후에도 일부 대화 상담원이 플레이어에게 계속 집중하도록하는 버그를 수정했습니다.
- 플레이어가 메뉴를 열 때 은신처에서 나이트 폴 바 재설정 대기 문제를 해결하십시오.

### 기타
- 쉴드 히트 포인트 값은 사용 된 티어와 재료에 따라 재조정되었습니다.
- 농민은 더 이상 파수꾼으로 직접 업그레이드 할 수 없습니다.
- 일부 진영 부대의 통계는 진영 균형을 유지하기 위해 수정되었습니다.
- 토너먼트는 이제 독점적이고, 약하고, 쉽게 쉴 수있는 방패를 갖게됩니다.
- 우리의 스토리 라인 형제는 이제 더 싼 갑옷을 입으므로 플레이어는 자신의 장비로 그를 벗길 가능성이 적습니다.
- 모든 Sturgian 진영 부대는 이제 둥근 방패를 사용합니다. 또한 레벨과 능력에 더 적합한 방패를 사용합니다.
- 오래된 저장 파일로 게임을 계속 한 플레이어가 굶어 죽지 않는 버그가 수정되었습니다.

## 멀티 플레이어
### 게임 모드
- 캡틴 모드에서 때때로 패배하는 이유가 수정되었습니다.
- 선장 모드 스폰에서 병력 얼굴 무작위 화가 수정되었습니다.

### 기타
- 주어진 시간 동안 허용 된 시간보다 게임을 떠난 플레이어를위한 쿨 다운이 추가되었습니다. 현재 지난 3 시간 동안 매치 메이커 게임을 2 번 떠난 플레이어는 15 분 동안 매치 메이킹이 차단됩니다. 참고 :이 값은 필요한 경우 또는 문제가 발생하는 경우 패치를 요구하지 않고 언제든지 가능합니다.

### 서버 & 네트워크
- 매치 메이커 게임에 대한 진영이 이제 균등하게 분배됩니다.
- 멀티 플레이어 팀 데스 매치에 들어가는 동안 충돌이 수정되었습니다.
- 공식 커스텀 게임에는 치트 방지가 필요합니다.

### UI
- HUD에 서버 상태 비주얼 시스템을 추가했습니다.
- 매치 메이킹 탭의 미세 조정 및 개선
- 병과 선택 화면에서 상단에있는 병력 유형 아이콘 (플레이어 아바타 근처)이 35 % 더 커졌습니다.
- 캐릭터 커스터마이즈 의상 옵션이 작동하지 않던 것을 고쳤습니다.

## 공통 사항

### 충돌
- 로딩 화면에서 ESC 키를 누르면 무한 루프가 발생합니다.

### 아트
- 조명 조정.
- 일부 스톤 메시의 시차 문제를 수정했습니다.

### 애니메이션
- 새로운 핸드 쉴드 액티브 디펜스 애니메이션.
- 핸드 쉴드 방향 각도를 보호하십시오.
- 일부 라이더 가을 애니메이션의 블렌드 지속 시간이 제거되었습니다.
- 낙타에 새로운 유휴 애니메이션이 추가되었습니다.
- 말에서 떨어지는 라이더는 서있을 때만 막을 수 있습니다.

### 오디오
- 구성 파일에서 사운드 장치가 비활성화되는 문제를 해결했습니다.

### UI
- 십자선 가시성을 향상시키기 위해 십자선 외곽선을 추가했습니다.
- 게임 플레이 옵션에 새로운 "수직 조준 보정"옵션이 추가되었습니다.
- 비디오 옵션에 새로운 "메뉴의 ForceVSync"옵션을 추가했습니다.

### AI 전투
- 기병대는 근접 공격에서 회전을 조정하는 데 어려움을 겪었으며 특히 두 명의 AI 요원이 서로 싸울 때 서로 돌릴 수 있었으므로이 문제와 관련하여 크게 개선되었습니다.

### 성능
- 많은 HDD 스파이크 문제가 수정되었습니다.
- 전투 중 메모리 할당이 줄어들고 일부 인공 지능이 최적화되었습니다. 전투 중에 발생하는 스파이크를 줄여야합니다.
- 봉제 인형 및 아이템 삭제 성능 향상.
- 멀티 코어 성능 향상
- 트레일 효과의 성능이 향상되었습니다.

### 기타
- 바위는 이제 요원을 쓰러 뜨릴 수 있습니다.
- 던진 바위가 멈춘 후의 스케일 변경을 수정했습니다.
- 말은 더 이상 사다리에 올라갈 수 없습니다.
- 시체는 이제 주변과 함께 추가 피를받습니다.

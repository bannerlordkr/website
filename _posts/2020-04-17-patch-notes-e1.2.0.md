---
layout: post
style: post
categories: news patchnote
thumbnail: https://steamcdn-a.akamaihd.net/steamcommunity/public/images/clans/26623866/bd5a2f819c3dbb1c706d81ec700a5f8b9c0d21a2.png
title: 패치 노트 e1.2.0
date: 2020-04-17 00:00:00 +0900
author: Noobplayer(dold****)
source: https://cafe.naver.com/warband/253854
comments: true
---

## 버전
    네이티브: e1.2.0
    샌드박스코어: e1.2.0
    샌드박스: e1.2.0
    스토리 모드: e1.2.0
    커스텀 배틀: e1.2.0

# 싱글플레이어
## 충돌
- 산의 계절이 변화하는 동안 산에 접근할 때 발생되는 충돌 수정
- 영웅 포로들을 처형시킬 때 발생하는 충돌을 수정

## 성능
- UI에서 일어나는 메모리 누수 현상 몇몇을 해결하므로서 VRAM 사용량 감소. 
- 미션들간에 일어나는 충돌 수정.
- 월드맵에서 GPU메모리 사용량 약간 감소.

## 세이브 & 로드
- 이전 버전에서 세이브된 파일을 불러올 때 스킬 레벨이 보존됨.

## 번역
- 중국어 번체 추가.
- 몇몇 문법적 오류들이 수정되고 폰트가 수정됨.
- 중국어 간체와 터키어 번역의 추가,개선,교정.

## 아트
- AI를 위한 도주 지점들이 전투 지형에 추가됨.
- 아세라이 마을들 중 하나에서 발생한 그래픽 문제 몇가지 수정
- 블란디아 뱅가드 쉴드 문양 문제 수정
- 꽃 위에 피를 렌더링할 때 발생하는 그래픽 오류 수정
- 제작에 새로운 3가지 아이템이 추가됨. - 한 가지의 검집과 두 가지의 스피어 날
- 아이템 제작시 발생하는 문제들 몇가지 수정

## UI
- 맵 알림들이 때때로 플레이어에게 보여지지 않고 사라지는 버그 수정

## 전투와 공성전
- 적을 약탈할 때, 적이 소유한 아이템의 가치가 너무 낮거나 너무 높다면 시스템이 변수에 따라 아이템을 다르게 제공할 수 있음.
- 화살들이 공성 사다리 계단 사이로 통과할 수 있음.
- 시체들과 투석기에서 던져진 돌들이 사라지지 않는 현상 수정

## 전투 AI
- 공성전에서 AI들이 예기치 않은 행동을 하고 충돌을 불러 일으키기도 하는 치명적 버그 수정 
- 정적 네비게이션 메쉬에서 동적 네비게이션 메쉬로 바뀔 때, 그 반대의 경우도 마찬가지로 AI 길찾기가 거의 항상 초기화 되는 치명적 버그 수정. (이 버그로 인해 성능 저하가 발생하고 AI들이 공성탑에 적절하게 올라가지 못함) 
- 팀의 장군이 공성 배치단계에서 선택되지 않도록 하는 부적절한 행동 명령 수정
- 공성전에서 외부 게이트를 부신 후에도 내부 게이트를 공격해야하는 AI들이 랜덤하게 성채 사다리로 올라가려는 버그 수정. (이 버그 때문에 게이트 바깥 쪽에 AI들이 서서 기다렸음.)
- 부대가 서로 흩어지려 할 때, 후퇴하도록 명령했을 때 적을 향해서 도망가는 버그 수정.
- 공성전에서 성능 하락을 일으키는 불필요한 AI 길찾기 호출 제거. 길을 찾는데는 문제 없음.

## 캐릭터 시스템
- 스킬 경험치 포인트 증가 공식이 10 + 스킬 레벨로 변경됨.
- 캐릭터 생성시에 남성에서 여성으로 바꿀때 모든 남성적 특성들(ex 수염)이 초기화됨.

## 클랜과 파티
- 동료들은 더 저렴한 아이템을 지니고 등장함, 그래서 더 쉽게 고용할 수 있음.

## 경제와 무역
- 고티어 아머들이 마을에서 생산되고 때때로 시장에서 발견될 수 있음.

## 제작
- 제작 아이템들이 제작 전에 보여준 스텟과 다른 현상 수정.
- 세이브 파일을 불러올 때 제작 아이템들의 스텟 변화 현상 수정

## 정착지 행동
- 건설 가속화 퍽이 이제 2배 건설 속도 증가 대신에 50 건설 속도가 추가됩니다.
- 동료들에게 동료들의 위치를 물어보는 문제와  마을 사람들에게 같이 있는 동료를 물어보는 문제 수정
- 정착지 프로젝트 완성 시간이 마이너스가 되는 버그 해결

## 퀘스트 & 이슈
- 가족 불화 퀘스트 관련 수정/개선 사항
    - 버그
        - 세이브 & 로드 후에 퀘스트 일지가 사라지는 버그 수정
        - 목적 마을에 퀘스트 NPC가 생성되지 않는 버그 수정
    - 개선 사항
        - 퀘스트 일지 무장 몇 가지 추가 및 수정
        - 로그 항목 몇 가지 추가 및 수정
        - 만약 유저가 퀘스트 NPC를 파티에서 내쫓는다면 퀘스트는 실패함.
    - `우리 사이에 스파이가 있어(스파이 파티)` 퀘스트 관련 수정/개선 사항
        - 일반
            - 퀘스트 제목이 `우리 사이에 스파이가 있어`]`로 변경됨.
            - 지금부터 유저들은 퀘스트 수여자가 부대 안에 있더라도 퀘스트를 발동시킬 수 있음.
        - 수정
            - 스파이 후보자들의 얼굴 단서들이 변하는 버그 수정
            - 스파이와 일기토할 때 유저들에게 UI 체력 창이 잘못된 값을 보여주는 버그 수정
            - 세이브 & 로드할 때 스파이 후보자들이 사라지는 버그 수정
        - 개선사항
            - 스파이는 유저들의 스킬에 따라 조절됨.
            - 스파이에게 더 나은 전투 장비가 제공됨.
        - 퀘스트 일지 문장 몇 가지 추가 및 수정
            - 마을 사람들이 유저들에게 단서를 주는 랜덤 변수들이 문제를 일으키지 않도록 조절됨.
            - 스파이 후보자들의 비주얼 추적이 추가됨. (기본값: Alt 키)
            - 문제 기간이 35일에서 5일로 변화됨.
    - `로드는 선생님이 필요해` 퀘스트 관련 수정/개선 사항
        - 수정
            - 유저가 죄수가 된 후에 퀘스트 NPC가 사라지는 버그 수정
            - 퀘스트 수여자와 퀘스트 NPC가 같은 사람인 버그 수정
        - 개선 사항
            - 로그 항목 몇 가지 추가 및 수정
            - 만약 유저와 퀘스트 NPC가 어떻게 해서든지 분리된다면 유저들은 추적할 수 있게되고 퀘스트 NPC를 퀘스트 로그를 통해서 찾을 수 있게됨. 따라서 계속 퀘스트를 진행할 수 있음.
    - `로드는 라이벌을 사로잡길 원해` 퀘스트 관력 수정/개선 사항
        - 수정
            - 퀘스트 수여자가 영지를 가진게 없다면 퀘스트가 멈추는 버그 수정
            - 복제되거나 빈 로그 항목을 생성하는 버그 수정
        - 개선 사항
            - 유저들이 목표 NPC를 퀘스트 수여자에게 전달할 수 있는 일지 옵션 추가.
    - 촌장은 곡식이 필요해 퀘스트 문제 해결
    - 더나은 퀘스트 일지 개선
    - 몇 가지 퀘스트에서 설득 변수가 수정됨.

## 기타
- 마이너 팩션이 그들의 특성에 더 적합하도록 장비들이 수정됨. 
- 두 번째로 마을에 들어갈 때, 문지기들이 사라지는 문제 수정
- 적대 진영에 들어갔을 때 유저 동료 초상화의 색감이 수정됨
- 유저들의 형제가 좀 더 어려지도록 함.
- 죄수가 통치자가 되는 버그 수정.
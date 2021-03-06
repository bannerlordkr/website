---
layout: post
style: post
categories: news patchnote
thumbnail: https://steamcdn-a.akamaihd.net/steamcommunity/public/images/clans/26623866/054363467a0e5862f083e291301b411866a69937.png
title: 패치 노트 e1.0.4
date: 2020-04-04 00:00:00 +0900
author: 토보에(cami****)
source: https://cafe.naver.com/warband/247802
comments: true
---

## 버전
    네이티브: e1.0.0
    샌드박스코어: e1.0.4
    샌드박스: e1.0.4
    스토리 모드: e1.0.4
    커스텀 배틀: e1.0.4

## 멀티플레이 튕김 현상
- 드물게 특정 전투관련 네트워크 메세지가 잘못된 순서로 수신될 때 클라이언트가 충돌하는 문제 해결

## 싱글플레이 튕김 현상
- 공성전과 관련된 드문 예외 현상 수정
- 캠페인 지도상에서 이동 중 튕기던 현상 수정
- 가문 깃발 편집기를 닫은 뒤 튕기던 현상 수정
- 마을 약탈 행동을 하던 중 적군 영주와 조우 이후 마을주민 대화창에서 튕기던 현상 수정
- 부대창에서 부대원 위치를 옮기던 중 발생하던 튕김현상 수정
- 캠페인 맵에서 나가던 중 발생하던 튕김현상 수정
- 인벤토리에서 수량을 0으로 조절할 때 발생하던 튕김현상 수정
- 공성당하는 아군 정착지로 들어갈 때 발생하던 튕김현상 수정
- 플레이어가 전투에 패배한 편에 있었을 때, 전투 후 나오는 대화상대가 비영웅 캐릭터일 때 튕기던 현상 수정.
- 은신처에 있던 적을 모두 처치한 후 은신처 보스가 나오기 전 튕기던 현상 수정
- 플레이어가 NPC가 보드게임을 마치고 튕기던 현상 수정
- 공성 준비중인 상태일 때 방해받은 뒤 공성을 진행하면 튕기던 현상 수정
- 말을 탄 에이전트를 타게팅 할 때 튕기던 현상 수정
- 무기를 모아 달라는 갱 리더 관련 퀘스트 시 무기를 모두 수집한 후 로딩했을 때 튕기던 현상 수정
- 드물게 캐릭터 생성 시 옵션을 선택할 때 튕기던 현상 수정
- 드물게 캐러반 관련으로 돈이 오갈 때 튕기던 현상 수정

## 최적화
- 특히 공성전 중에 엄청난 렉을 유발하던 NPC 관련 길찾기 시스템 문제 수정 
- 메모리 누수 현상 수정

## 세이브 & 로드
- 세이브 로드 시 안정성 개선

## 전투 관련
- 공성중인 부대를 공격할 때 야전에서 싸우지 않고 공성전으로 전투가 진행되던 문제 수정
- (p.s 이렇게 전투가 시작되면 야전 AI가 공성전인 맵에 적용되서 AI 움직임이 바보가 되었습니다) 

## 전투 AI
- 원거리 유닛의 야간 디버프, 시야 제한, 추가적인 조준 오류를 제거

## 클랜과 부대 관련
- 배너 편집기에서 오픈 핸드 문제를 수정 (Fixed the open hands issue in the banner editor)
- 캠페인에서 일정 시간이 지났을 때 재정 관련 문제로 몇몇 군주들이 부대원없이 돌아다니다 산적이나 도적들에게 괴롭힘 당하던 현상을 수정. 이제 군주들은 재정을 더 효율적으로 관리하고 파산할 위기에 처하면 성에서 주둔군을 빼서 쓰게됨. 캠페인에서 특정 국가가 너무 급격하게 멸망하고 스노우볼링 당하던 문제의 원인 중 하나였음. 
- 임신과 관련된 사소한 문제 수정
- 유저의 클랜 멤버가 정착지에서 끼이던 문제 수정

## 왕국과 외교
- `일시 휴전 거래(Safe passage barter)` 이후 방어 전투와 관련된 문제 수정

## 제작
- 대장간에서 도끼 못 만들던 문제 수정

## 이슈 & 퀘스트
- `밀렵꾼(Poachers)` 퀘스트 막바지에 AI가 공격하려고 하던 문제 수정

## 기타
- 200개가 넘는 아이템이 게임에 다시 도입됨 (아이템 코드에 멀티플레이에 사용된다는 코드가 한 줄 추가되어 있던 아이템들은 캠페인에 나오지 않았었는데 그걸 수정한 것 같습니다)
- 방어 수치와 가격 재조정
- 도시 상점에 등장하는 무기와 방어구와 관련된 부분을 재조정함
- 아세라이 기본 징집병은 `Aserai Recruit`가 되었어야 했는데 `Aserai Tribesman`이 기본 징집병이던 문제 수정. 

---
layout: post
title:  주차 위치유도 장치기들 통합 관리서버 아이템
date:   2022-05-30 15:01:35 +0300
image:  Integrated-monitoring.jpg
tags:   Resources
---
참슬테크에서 개발된 H/W, S/W에 대한 아이템들 입니다.

# 12면 주차유도

## H/W
* 12면 카메라
* PCM
* L2
* 입구 전광판
* 층별 안내판
* NVR

## S/W
### 윈도우
* 객체인식기
* CMS ManageAI(Main)
* 관리서버(Mapviewer)
* 홈넷연동

# 6면 카메라

## H/W
* 6면 카메라
* POE
* L2
* L3
* NVR

## S/W
### 윈도우
* 객체인식기
* CPLSManageAI(Main)
* 관리서버(Mapviewer)
* 기타 (주차관제연동, 홈넷연동)

# 원패스

## H/W
* 키등록기

## S/W
### 윈도우
* 원패스서버
* 기타 (주차관제연동, 홈넷연동)
### 리눅스
* Dev_Process
* Main_Process
* Ukrlan_Process
* E/V_Process

# 유선비상벨

## H/W
* 비상벨
* 릴레이장치
* ACU(PCU)
* L2

## S/W
### 윈도우
* CST Server
* 기타 (E/V연동, 홈넷연동)
* CCTV연동
* 방송연동
### 리눅스
* Dev_Process
* Main_Process
* H/N_Process
* E/V_Process
* G/W_Process
* View_Process

# 무선비상벨

## H/W
* 무선스위치
* 무선중계기
* ACU(PCU)

## S/W
### 윈도우
* 관리서버(Mapviewer)
* CCTV연동
### 리눅스
* ESS_Loc_Process
* ESS_Main_Process
* UPISInterface_Process
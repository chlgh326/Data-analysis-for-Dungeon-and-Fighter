# -
던전앤파이터 API에서 수집할 수 있는 데이터를 분석합니다.


# 던전앤파이터 경매장 등록 아이템 가격 예측 모델 개발


## 개요

- 던전앤파이터 API를 이용해 경매장에 등록된 아이템을 수집하고 활용하여 가격 예측 모델을 만듭니다.  


## 가격 예측 아이템

- '시간의 결정' 


## 데이터 수집 

- 수집: 네오플 오픈 API (https://developers.neople.co.kr/)
- 기간: 8/4 ~ 8/18일 (현재 적용: 8/4 ~ 8/7일) 


## 데이터 분석 (8/23일 완료 예정)
#### Table of contents
* [Data crawling](#1) 
* [Loading Data](#2) 
* [Initial Exploration](#3) 
* [Data Cleansing](#4) 
* [Feature engineering](#5) 
* [Data Partitioning](#6)       (현재 진행 중인 위치)
* [Modeling - XGboost](#7)
* [Check Feature Importance](#8)
* [Feature selection](#9)
* [Modeling - Bidirectional LSTM](#10)
* [Performance evaluation](#11)

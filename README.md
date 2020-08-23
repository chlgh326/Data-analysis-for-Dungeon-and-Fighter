# 던전앤파이터 경매장 등록 아이템 가격 예측 모델 개발


## 개요

- 던전앤파이터 API를 이용해 경매장에 등록된 아이템을 수집하고 활용하여 가격 예측 모델을 만듭니다.  


## 가격 예측 아이템

- '시간의 결정' 


## 데이터 수집 

- 수집: 네오플 오픈 API (https://developers.neople.co.kr/)
- 기간: 8/4 ~ 8/20 일

## 분석 코드 링크

- https://www.kaggle.com/chimiro/d-f-data-analysis

## 데이터 분석
#### Table of contents
* [Data crawling](#1) 
* [Loading Data](#2) 
* [Initial Exploration](#3) 
* [Data Cleansing](#4) 
* [Feature engineering](#5) 
* [Data Partitioning](#6)       
* [Modeling - XGboost](#7)
* [Check Feature Importance](#8)
* [Modeling - Bidirectional LSTM](#9)  <== (현재 진행 중인 위치) 
* [Performance evaluation](#10)

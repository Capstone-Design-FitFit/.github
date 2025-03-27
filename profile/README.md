# 캡스톤 디자인 프로젝트

## 프로젝트 제목
**가상 피팅 최적화 서비스: 자세 유사도 분석 및 신체 트래킹 기반**  
*Virtual Try on Optimization Service through Pose Similarity Analysis and Body Tracking*

## 팀원 소개

|<img src="https://avatars.githubusercontent.com/u/75584814?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/137462767?v=4" width="150" height="150"/>|
|:-:|:-:|
|Jinsoo Park<br/>[@jinny908](https://github.com/jinny908)|Jayoung Kim<br/>[@jaeyo03](https://github.com/jaeyo03)|

---

## 목차
1. [프로젝트 소개](#프로젝트-소개)
2. [프로젝트 목표](#프로젝트-목표)
3. [주요 기능](#주요-기능)
4. [진행 방법 및 아키텍처](#프로젝트-진행-방법-및-아키텍처)
5. [결과 및 성과](#프로젝트-결과-및-성과)
6. [향후 개선 방향](#향후-개선-방향)
7. [데모 영상](#데모-영상)

---

## 프로젝트 소개

**가상 피팅(Virtual Try-on)**이란 사용자가 원하는 옷을 특정 모델에게 가상으로 입혀보는 기술입니다. 본 프로젝트는 사용자의 자세를 BlazePose를 이용해 분석하고, 최적의 자세를 취했을 때 가상 피팅의 품질이 향상됨을 입증하고자 합니다.

---

## 프로젝트 목표
- 사용자가 선택한 옷을 더 정확하게 입혀보는 가상 피팅 서비스 제공
- 자세 유사도를 분석하여 최적의 자세를 가이드하고, 사용자의 자세를 실시간으로 평가
- 다양한 체형과 자세에서도 정확한 피팅 결과를 제공할 수 있는 시스템 구축

---

## 주요 기능

### 1. 자세 유사도 분석
- BlazePose를 활용한 정확한 신체 트래킹
- 코사인 유사도 기반으로 자세 유사도 수치화

### 2. Grid 기반 가상 피팅
- 자세 유사도 점수가 0.9 이상일 때 최적 피팅 진행
- 사용자가 최적의 자세를 쉽게 취할 수 있도록 화면에 그리드 표시

### 3. 반응형 UI
- 모바일과 데스크탑 모두에서 원활한 사용 경험을 제공하도록 UI 설계

---

## 프로젝트 진행 방법 및 아키텍처

### 시스템 아키텍처
- 사용자가 의류 선택 및 최적 자세 촬영
- 촬영된 자세의 유사도 평가
- Stable Viton 기반의 고품질 가상 피팅 처리

### 다이어그램
- Use Case Diagram
- Sequence Diagram
- Class Diagram

---

## 프로젝트 결과 및 성과

### 결과
- **SSIM (Structural Similarity Index Measure)**: 1에 가까울수록 원본 이미지와 유사도가 높음
- **LPIPS (Learned Perceptual Image Patch Similarity)**: 0에 가까울수록 원본 이미지와 유사도가 높음

### 성과
- 한국IT서비스학회 논문 제출 및 발표
- Wrtn Ideathon 대회 참가

---

## 향후 개선 방향
- 사용자가 따라할 수 있는 다양한 자세 추가
- 다양한 체형에 대응하는 모델 설정 기능 추가
- 더욱 성능이 뛰어난 가상 피팅 모델 도입 계획

---

## 발표 영상
[발표 영상 바로가기](https://www.youtube.com/watch?v=3Z11fcEMB6k)



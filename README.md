# 피부 분석 및 피부 예보 알리미 웹사이트 - 위드스킨 프로젝트

* [위드스킨 웹사이트 바로가기](http://knu-project.withbecon.com/)
* [최종 보고서 - PDF 파일](https://drive.google.com/file/d/1Q4QEwmEG4LkOG1r6Uv2siOngJXAZ2xSs/view?usp=sharing)
* ![[image](https://drive.google.com/file/d/1Q4QEwmEG4LkOG1r6Uv2siOngJXAZ2xSs/view?usp=sharing)](https://github.com/0Rumi1/withskin_project/assets/122415320/63573ec6-8525-41b7-b163-93d0c4da59cc)


## 프로젝트 기간
* 2023.05.03 – 06.16
* 협업툴: 노션 (프로젝트 일정 관리 및 문서 공유) [위드스킨 노션 팀페이지](https://romantic-colt-44b.notion.site/Home_-b3866c240e8f4ae99f6e35cdb9e47821?pvs=4)
* 메신저툴: 슬랙

<br>

## 프로젝트 배경
* 위드비컨이 가진 디자인/자원과 BM을 고려한 서비스 설계
1. 시간/비용적으로 피부과 방문이 부담스러운 소비자
2. 언제 나타날지 모르는 피부 트러블의 공포
3. 급변하는 온도, 건조한 날씨, 미세먼지 등 피부에 영향을 미치는 외부환경

<br>

**개발 방향 및 목표는 아래와 같다.**

* 위드비컨의 컬러 & 위드비컨 APP의 UI/UX 고려
* 두피에 사용하던 국소부위 촬영 디바이스를 피부 촬영에 활용

1. 디바이스 + 모바일웹, 어디서든 쉽고 빠른 피부 진단
2. AI 분석으로 현재 피부 상태 시각화 및 포피린 수치를 통해 피부 문제 예방
3. 날씨 API 연동, 외부 환경에 따른 대응요령을 제공하여 피부 문제 예방

## 프로젝트 설명
현재 피부 상태를 빠르고 정확하게 분석하는 편리성과 또래 중 상위 피부와 비교 및 등급을 통한 동기부여 그리고 직관적인 그래프와 수치를 통해 피부 문제를 예방하도록 돕는다. 

<br>

## 멤버 및 역할
* 멤버: 총 4명
* PM&디자인, 프론트엔드, 백엔드, DL&서비스배포 역할로 나뉨
  
* PM&디자인 역할 담당
1. 데이터 수집 및 자료 조사
2. UI/UX 디자인 (피그마)
3. 프로젝트 일정 관리
4. 피부 항목별 점수화



<br>

## 서비스 주 기능
![image](https://github.com/0Rumi1/withskin_project/assets/122415320/5550dada-9471-4e5c-9de6-6c24f48d735a)

 <br>


## 프로젝트 일정
[노션 프로젝트 일정 페이지 참고](https://romantic-colt-44b.notion.site/f0b95ae246d94f6db03c30a1c558d14e?v=8f34c461c3434385a9b29b195c23b57c&pvs=4)
![image](https://github.com/0Rumi1/withskin_project/assets/122415320/9adcb7b5-cfae-486a-bc59-75a8a27dd927)


 <br>

## 데이터

* 데이터 총 개수 : 658장
* 수집 방법은 크게 2 가지로 구분
1. 교육생들을 대상으로 직접 촬영한 사진 : 490장
2. withbecon 측에서 제공한 사진 : 168 장

[데이터 항목]
* uv/white 사진 > 피지, 포피린, 민감도(붉은 부위)
* 피부 수분(더미)
* 피부 온도(더미)
![image](https://github.com/0Rumi1/withskin_project/assets/122415320/1b1984fd-30d3-47ea-ae9b-a3c44225adde)



<br>

## 목차
1. [기획](#기획)
3. [개발](#개발)
4. [결과](#결과)
5. [리뷰 및 개선 사항](#리뷰-및-개선사항)
<br>

## 기획

* 시스템 구조도
![image](https://github.com/0Rumi1/withskin_project/assets/122415320/4048d78c-a79c-4007-8c95-afd752775a5e)

* 유저플로우 (피부 분석하기)
![image](https://github.com/0Rumi1/withskin_project/assets/122415320/04994463-b719-497c-a21b-ccd6dda2a719)

* 테크니컬플로우 
![image](https://github.com/0Rumi1/withskin_project/assets/122415320/bd3867d2-0701-40c2-8d57-d65fec8ea725)

* [요구사항 정의서 - 노션 페이지](https://romantic-colt-44b.notion.site/39a4a1bbade64515b9f6132175bdf0c6?v=20a6d5e3e92f445c87c3e60d701c3361)
![image](https://github.com/0Rumi1/withskin_project/assets/122415320/45b06bca-59dc-44ae-8110-c58a9ae287bf)


<br>

## 개발
### 개발환경
![image](https://github.com/0Rumi1/withskin_project/assets/122415320/6edc75c9-9130-4473-bd1b-3807f2a9a453)

### DB 설계
![image](https://github.com/0Rumi1/withskin_project/assets/122415320/02689ab1-b67e-4b3d-8d80-15fa4080e1a6)


### 배포환경
![image](https://github.com/0Rumi1/withskin_project/assets/122415320/2fd6f52e-ad98-4a5e-b02b-ea2cdbb58ec6)



<br>

## 결과

* [위드스킨 웹사이트 바로가기](http://knu-project.withbecon.com/)

* [최종 보고서 - PDF 파일](https://drive.google.com/file/d/1Q4QEwmEG4LkOG1r6Uv2siOngJXAZ2xSs/view?usp=sharing)
* ![image](https://github.com/0Rumi1/withskin_project/assets/122415320/63573ec6-8525-41b7-b163-93d0c4da59cc)


* 보고서
1.  [프로젝트계획서](https://drive.google.com/file/d/1mDwmQr2CIinOgaGovXvLC7QI67anQFJl/view?usp=sharing)
2.  [중간보고서](https://docs.google.com/document/d/1onoFTY8g6UlgV48Ro_3Xbzlh6bhZ-H0i-tBMiHB7x2U/edit?usp=sharing)
3.  [결과보고서](https://docs.google.com/document/d/1rxOshw49gyNlZIUAh1DBGo6FjvNhXlD7-eSltPVgtao/edit?usp=sharing)


<br>

## 리뷰 및 개선사항
* 마이페이지, 히스토리 기능 추가
  * DB에 유저 정보, 과거 문진 내역 등이 이미 저장되어 있으므로 해당 데이터를 바탕으로 기능 구현 가능
* api를 활용한 로그인
  * 세션 방식이 아닌 JWT 토큰 방식으로 변화시킬 경우 타 플랫폼 로그인 api 사용 가능
* 소통 및 문서화
  * 회의 후 변경된 내용 및 기능 등을 문서에 바로 수정 적용하여 서로간의 혼란이 없도록 하는 것이 중요

<br>



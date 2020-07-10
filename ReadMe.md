# Tnkfactory SDK Rwd

TnkAd SDK는 Tnk의 광고 네트워크 상에서 광고앱 이나 매체앱을 개발하기 위하여 제공되는 통합된 SDK이며 아래의 기능들을 사용하실 수 있습니다.

* 보상형/구매형 광고의 오퍼월(Offer-wall)
* 보상형 전면광고(Interstitial Ad)
* 분석도구(Analytics) 기능 제공으로 유입경로 별 앱사용율, 재방문율, 퍼널분석 등의 다양한 분석보고서 생성

## iOS

### iOS Guide

[iOS 가이드 문서](./iOS_Guide.md)

### Update Notice

* 2020.07.07 
  * v4.21 업데이트
    *  오퍼월 처음 띄우는 시점에 개인정보 수집 동의 창 띄우도록 기능 추가
* 2019.12.30
  * v4.20 업데이트
    * 오퍼월 UI Autolayout 으로 재구현
    * 내부 기능 개선
* 2019.11.28
  * v4.19
    * 보상형 광고리스트(오퍼월) 기능 추가
      * Header 영역 커스터마이징 기능 추가 : [TnkSession sharedInstance].adListSectionHeaderView = UIView 지정
      * Modal 로 띄울 경우 닫기버튼에 이미지 설정 기능 추가 : [TnkSession sharedInstance].headerCloseButtonImage = UIImage 지정


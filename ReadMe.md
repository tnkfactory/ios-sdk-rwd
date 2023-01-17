# Tnkfactory SDK Rwd

TnkAd SDK는 Tnk의 광고 네트워크 상에서 광고앱 이나 매체앱을 개발하기 위하여 제공되는 통합된 SDK이며 아래의 기능들을 사용하실 수 있습니다.

* 보상형/구매형 광고의 오퍼월(Offer-wall)
* 분석도구(Analytics) 기능 제공으로 유입경로 별 앱사용율, 재방문율, 퍼널분석 등의 다양한 분석보고서 생성

## iOS

### iOS Guide

[iOS 가이드 문서](./iOS_Guide.md)

### Update Notice

* 2023.01.17
  - v5.44 업데이트
    - headerTextColor, detailHeaderTextColor 설정 동작안하는 버그 수정
* 2022.12.26
  - v4.42 업데이트
    - queryAdvertiseCount 성능 개선
* 2022.10.12
  - v4.40 업데이트
    - 내부 memory leak 버그 수정
* 2022.09.30
  - v4.39 업데이트
    - 오퍼월 커스터마이징 기능 개선
* 2022.08.30
  - v4.37 업데이트
    - 오퍼월 추척허용 안내 팝업에서 설정화면으로 바로가는 기능 추가 
* 2022.05.30
  - v4.36 업데이트
    - 오퍼월 하단의 문의하기 버튼 안보이는 버그 수정 
* 2022.04.26
  - 배포방식을 기존 lib 파일에서 xcframework 로 변경하였습니다.
* 2021.11.03
  - v4.31 업데이트
    - 내부 버그 수정
* 2021.03.12
  - v4.29 업데이트
    - 오퍼월에 구매형상품(CPS) 추가
    - 오퍼월에 광고 종류별 선택가능한 탭 기능 추가
    - 오퍼월 기본 디자인 및 커스터마이징 항목 추가/수정
    - iOS9 에서 Deprecated 된 API 중 일부 수정
* 2021.02.26
  - v4.28 업데이트
    - iOS14 대응 (보상형 광고)
    - 오퍼월 리스트 기본 디자인 수정
    - iOS 최소 지원 버전 : iOS 9.0
* 2020.12.18
  - v4.27 업데이트
    - 유니티에서 오퍼월 강제종료 버그 수정
* 2020.10.15
  - v4.24 업데이트
    - iOS14 대응
* 2020.07.07 
  * v4.21 업데이트
    *  오퍼월 처음 띄우는 시점에 개인정보 수집 동의 창 띄우도록 기능 추가
* 2019.12.30
  * v4.20 업데이트
    * 오퍼월 UI Autolayout 으로 재구현
    * 내부 기능 개선
* 2019.11.28
  * v4.19 업데이트
    * 보상형 광고리스트(오퍼월) 기능 추가
      * Header 영역 커스터마이징 기능 추가 : [TnkSession sharedInstance].adListSectionHeaderView = UIView 지정
      * Modal 로 띄울 경우 닫기버튼에 이미지 설정 기능 추가 : [TnkSession sharedInstance].headerCloseButtonImage = UIImage 지정
* 2019.11.19
  * v4.18 업데이트
    * iOS13, iPhone11 지원
    * COPPA, GDPR 설정 기능 추가
    * 4.18b : iOS13에서 NavigationBar 높이 계산오류가 있어서 work-round 처리
* 2018.05.14
  * v4.16 업데이트
    * 전면광고 프레임 신규디자인 추가
    * NativeAd 에 소재 2 종류 추가 : AD_STYLE_BANNER_LANDSCAPE (720 x 100) , AD_STYLE_BANNER_LANDSCAPE (720 x 200)
* 2018.01.26
  * 4.15 업데이트
    * 보상형광고리스트용 UIView 제공
    * 보상형광고리스트 타이틀 영역에 이용문의 버튼 추가하는 기능
    * 보상형 광고리스트 하단의 Footer 영역 숨기는 기능 추가
* 2017.06.16
  * 4.14 업데이트
    * 2-button 전면 프레임의 라벨 지정 기능 및 닫기 버튼 위치 지정 기능 추가
* 2016.10.19
  * 4.13 업데이트
    * 전면광고 화면에서 (X) 버튼이 눌리지 않는 경우가 있어 수정함.
* 2016.09.22
  * 4.12 업데이트
    * TnkNativeAdManager 기능 추가 (한번에 여러건의 NativeAdItem 을 조회)
    * NativeAd 내부 기능 개선
    * 전면 2-버튼 프레임 모두 지원하도록 기능 추가
    * iOS10 지원, XCode v8.0으로 빌드.
* [Release Notes 더보기](./iOS_Release_Notes.md)


	---

copyright:
 years: 2015, 2016

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# {{site.data.keyword.mobilepushshort}} 시작하기
{: #gettingstartedtemplate}
마지막 업데이트 날짜: 2016년 8월 16일
{: .last-updated}

{:shortdesc}

{{site.data.keyword.mobilepushshort}} 서비스는 iOS 플랫폼과 Android 플랫폼을 대상으로 하는 모바일 {{site.data.keyword.mobilepushshort}}을 보내고 관리할 통합된 플랫폼을 제공합니다. {{site.data.keyword.mobilepushshort}} 서비스는 디바이스 플랫폼, 디바이스에 대한 애플리케이션 사용자의 맵핑을 관리하고 사용자에 대한 푸시 알림의 디스패치를 처리합니다. 이 서비스를 사용하면 브로드캐스트, 유니캐스트(디바이스 ID 기반), 태그(또는 주제)를 모바일 애플리케이션 사용자에게 푸시 알림으로 보낼 수 있습니다. 또한 SDK 및 [REST API](https://mobile.{DomainName}/imfpushrestapidocs/)를 사용하여 클라이언트 애플리케이션을 추가적으로 개발할 수도 있습니다. 

여기서는 기본 푸시 알림의 설정 방법에 대해 설명합니다. 기본 알림을 사용하는 경우 태그를 사용하여 특정 사용자 세트에 알림이 도달하는 것이 아니라 브로드캐스트됩니다. 

1. [알림 제공자에 대한 신임 정보 구성](t__main_push_config_provider.html)
2. [알림을 수신하도록 모바일 앱 설정](c_enable_push.html)
3. [기본 알림 전송](t_send_push_notifications.html)

# 관련 링크
{: #rellinks}

* [개요](c_overview_push.md){: new_window}

## 튜토리얼 및 샘플 {:id="samples"}
{: #samples}
* [Android helloPush 샘플 애플리케이션](https://github.com/ibm-bluemix-mobile-services/bms-samples-android-hellopush/){: new_window}
- [Cordova 샘플 애플리케이션](https://github.com/ibm-bluemix-mobile-services/bms-samples-cordova-hellopush){: new_window}
* [iOS helloPush 샘플 애플리케이션(Obj-C)](https://github.com/ibm-bluemix-mobile-services/bms-samples-ios-hellopush/){: new_window}
* [iOS helloPush 샘플 애플리케이션(Swift)](https://github.com/ibm-bluemix-mobile-services/bms-samples-swift-hellopush){: new_window}

## SDK
{: #sdk}
* [Android SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-android-push){: new_window}
* [Cordova SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-cordova-plugin-push){: new_window}
* [iOS SDK(Obj-C)](https://hub.jazz.net/git/bluemixmobilesdk/imf-ios-sdk/archive?revstr=master){: new_window}
* [iOS SDK(Swift)](https://codeload.github.com/ibm-bluemix-mobile-services/bms-clientsdk-swift-push/zip/master){: new_window}

## API 참조서
{: #api}
* [푸시 API 참조(Android)](https://classicdocs.ng.bluemix.net/docs/api/content/api/mobilefirst/android/push-api-doc/overview-summary.html){: new_window}
* [IMFPush API 참조 iOS](https://classicdocs.ng.bluemix.net/docs/api/content/api/mobilefirst/ios/IMFPush_api-doc/html/index.html){: new_window}
* [BMSPush API 참조 iOS(Swift)](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-swift-push/blob/development/Apple Docs/index.html){: new_window}
* [REST API 참조](https://mobile.{DomainName}/imfpushrestapidocs/){: new_window}

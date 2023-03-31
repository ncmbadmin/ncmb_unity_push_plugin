# NIFCLOUD Mobile Backend Push Notification Plugin for Unity


こちらはニフクラmobile backendのUnityプッシュ通知用プラグインになります。
利用方法については [ドキュメント](https://mbaas.nifcloud.com/doc/current/push/basic_usage_unity.html) をご確認し、ご利用ください。
こちらは単体では動きませんのでご注意ください。

---
## 動作環境

- Unity 2021.x
- Android 8.x〜12.x, API level 26.0〜31.0
- iOS 13.x〜16.x
(※2023年04月時点)

### テクニカルサポート窓口対応バージョン

テクニカルサポート窓口では、1年半以内にリリースされたSDKに対してのみサポート対応させていただきます。
定期的なバージョンのアップデートにご協力ください。  
※なお、mobile backend にて大規模な改修が行われた際は、1年半以内のSDKであっても対応出来ない場合がございます。  
その際は[informationブログ](https://mbaas.nifcloud.com/info/)にてお知らせいたします。予めご了承ください。  

- v1.0.0 ～ (※2023年4月時点)

[開発ガイドライン](https://mbaas.nifcloud.com/doc/current/common/dev_guide.html#SDK%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)をご覧ください。


## 初期設定

* 詳細については[ドキュメント](https://mbaas.nifcloud.com/doc/current/push/basic_usage_unity.html)を併せてご確認ください.
* Android端末での利用には、ご自身のFirebase設定ファイルgoogle-services.jsonをダウンロードして、Cordovaプロジェクトのルートディレクトリに置く必要があります。設定ファイルのダウンロードについては[こちらのFirebaseサポートページ](https://support.google.com/firebase/answer/7015592)にて詳細をご覧ください。

```
- Your_unity_project/
    platforms/
    plugins/
    www/
    config.xml
    google-services.json       <--
    ...
```

## ライセンス

LICENSEファイルをご覧ください。
